# Area_Line Chart JS - (Vital signs) <br>
The "AREA_LINE_CHART_JS" type chart uses two series: area and line within the same rendering.</br>

To use the 'AREA_LINE_CHART_JS' type chart, you need to make some settings:</br>

<b>1º - First configuration to be done, is to set the graph type to area_line.</b>

#### :pencil2: Examples: <br>

_Setting to change chart type to 'AREA_LINE'_<br>
```java
a = angular.element($0).scope()
a.handler.setChartProperties({
type:'area_line',
})
```
<b> 2º - É preciso setar via handler todos os valores das series do Chart.</b> <br>
To set the series of the Chart via the handler, the 'addAllSeries' function was created, so you must send all the series at once, so that the necessary calculations can be made on the part of the Framework, referring to all the series of AREA and LINE . *Use the same way as the 'addSeries' method, but using addAllSeries.

```java
WChartProperties chartProperties = new WChartProperties();
chartProperties.addPointsStyles(PointStyleEnum.CIRCLE);
```
_Configuration to set lines colors_<br>

```java
WChartProperties chartProperties = new WChartProperties();
ArrayList<String> linesColors = new ArrayList<>();
linesColors.add("#4F4F4F");
linesColors.add("#836FFF");
linesColors.add("#000080");
linesColors.add("#00BFFF");
linesColors.add("#00CED1");
linesColors.add("#DAA520");
linesColors.add("#DDA0DD");
linesColors.add("#FF1493");
chartProperties.setLinesColors(linesColors);
```

#### Full Example:
```java
import br.com.philips.tasy.dto.shared.wchart.WChartProperties;
import br.com.philips.tasy.dto.shared.wchart.WChartSeriesDTO;
import br.com.philips.tasy.dto.shared.wchart.WChartSeriesValueDTO;
import br.com.wheb.action.wChart.AbstractWChartPostProcessingAction;
import br.com.wheb.annotations.NamedAction;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

@NamedAction(name = "postProcessSeries", referedInterface = AbstractWChartPostProcessingAction.class)
public class TecTesF1WChartPostProcessingAction extends AbstractWChartPostProcessingAction {

    @Override
    public ArrayList<WChartSeriesDTO> build(ArrayList<WChartSeriesDTO> series, Integer dictionaryCode, Map<String, Object> params,
                                            ArrayList<HashMap> aditionalSeries, Map<String, Object> filterValues, WChartProperties chartProperties) {
        ArrayList<WChartSeriesValueDTO> values1stSerie = new ArrayList();
        ArrayList<WChartSeriesValueDTO> values2ndSerie = new ArrayList();
        ArrayList<WChartSeriesValueDTO> values3rdSerie = new ArrayList();
        ArrayList<WChartSeriesValueDTO> values4thSerie = new ArrayList();
        String[] dates = {
            "01/07/2018",
            "02/07/2018",
            "03/07/2018",
            "04/07/2018",
            "05/07/2018",
            "06/07/2018",
            "07/07/2018",
            "08/07/2018",
            "09/07/2018",
            "10/07/2018",
        };

        for (int i = 0; i < 10; i++) {
            values1stSerie.add(createValueDTO(dates[i],400 - 10 * i));
            values2ndSerie.add(createValueDTO(dates[i],50 * i));
            values3rdSerie.add(createValueDTO(dates[i],200 - 2 * i));
            if (i == 1) {
                values4thSerie.add(createValueDTO(dates[i], 0));
            } else {
                values4thSerie.add(createValueDTO(dates[i],100 * i - 75));
            }
        }

        for (WChartSeriesValueDTO value : values1stSerie) {
            series.get(0).getValues().add(value);
        }
        for (WChartSeriesValueDTO value : values2ndSerie) {
            series.get(1).getValues().add(value);
        }
        for (WChartSeriesValueDTO value : values3rdSerie) {
            series.get(2).getValues().add(value);
        }
        for (WChartSeriesValueDTO value : values4thSerie) {
            series.get(3).getValues().add(value);
        }

        // Configuration of chart properties 'LINE_CHART_JS'
        // Sets to type 'LINE_CHART_JS'
        chartProperties.setType(SerieType.LINE_CHART_JS);

	// Sets line colors
	ArrayList<String> linesColors = new ArrayList<>();
	linesColors.add("#4F4F4F");
	linesColors.add("#836FFF");
	linesColors.add("#000080");
	linesColors.add("#00BFFF");
	linesColors.add("#00CED1");
	linesColors.add("#DAA520");
	linesColors.add("#DDA0DD");
	linesColors.add("#FF1493");
	chartProperties.setLinesColors(linesColors);

        // Sets 'point style' of the FIRST series to type 'TRIANGLE'
        chartProperties.addPointsStyles(PointStyleEnum.TRIANGLE);

        // Sets 'point style' of the SECOND series to type 'STAR'
        chartProperties.addPointsStyles(PointStyleEnum.STAR);

        // Sets 'point style' of the THIRD series to type 'CIRCLE'
        chartProperties.addPointsStyles(PointStyleEnum.CIRCLE);

        // Sets 'point style' of the FOURTH series to type 'RECT_ROUNDED'
        chartProperties.addPointsStyles(PointStyleEnum.RECT_ROUNDED);

        return series;
    }

    private WChartSeriesValueDTO createValueDTO(Object axisX, Object axisY) {
        WChartSeriesValueDTO value = new WChartSeriesValueDTO();
        value.setPrediction(true);
        value.setValueAxisX(axisX);
        value.setValueAxisY(axisY);
        return value;
    }
}
```
