# Area_Line Chart JS - (Vital signs) <br>
The "AREA_LINE_CHART_JS" type chart uses two series: area and line within the same rendering.</br>

To use the 'AREA_LINE_CHART_JS' type chart, you need to make some settings:</br>

<b>- **It is necessary to set via handler all the values ​​of the Chart series.**</b> <br>
To set the series of the Chart via the handler, the 'addAllSeries' function was created, so you must send all the series at once, so that the necessary calculations can be made on the part of the Framework, referring to all the series of AREA and LINE . *Use the same way as the 'addSeries' method, but using addAllSeries.<br>
 >[!IMPORTANT]
   >Series AREA => remembering that the series of type area will be used only to assemble the back part, the backgound of the graphic, just for visual effects.<br>
Series LINE => the series of the line type will be the graph that will have the reference points meeting between the X, Y axes that when passing the mouse over will present the tooltip with the complementary information..

#### :bookmark_tabs: Parameters
**data:** _(Object)_ All graph series, both areas and lines. <br>

#### :pencil2: Examples: <br>
```javascript
const data: {
        columns: [
            ['data1', 900, 900, 900, 900, 900, 900],
            ['data2', 200, 130, 90, 240, 130, 220],
            ['data3', 300, 200, 160, 400, 250, 250],
            ['data4', 130, 120, 150, 140, 160, 150],
            ['data5', 100, 100, 100, 100, 100, 100],
        ],
        type: 'area_line',
        types: {
            data1: 'area',
            data2: 'area',
            data3: 'line',
            data4: 'area',
            data5:'area'
        },
        groups: [
            ['data1','data2', 'data3', 'data4']
        ]
    }
handler.addAllSerie(data);
```

<b>- **Set chart type to AREA_LINE in Chart settings**</b>

#### :pencil2: Examples: <br>

_Setting to change chart type to 'AREA_LINE'_<br>
```javascript
const chartData = {
 data,
  chartProperties: {
    title: chartTitle,
    type: 'area_line',
    propertiesNew: {}
  }
};
this.chartData = chartData;
```
