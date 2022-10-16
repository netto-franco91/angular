**maxTargetField (field type String) - this attribute allows the user to set the maximum target field**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMaxTargetField("maxTargetField");
```
**minTargetField (field type String) - this attribute allows the user to set the minimum target field**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetField("minTargetField");
```
**maxTargetValue (field type String) - this attribute allows the user to set the maximum target value**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMaxTargetValue("maxTargetValue");
```

maxTargetValue (String) - ex. wChartSeriesListDTO.getChartProperties().setMaxTargetValue("maxTargetValue")
minTargetValue (String) - ex. wChartSeriesListDTO.getChartProperties().setMinTargetValue("minTargetValue")
ieTargetType (String) - ex. wChartSeriesListDTO.getChartProperties().setIeTargetType("ieTargetType")
StringType (String) - ex. wChartSeriesListDTO.getChartProperties().setStringType("stringType")

Tipo(Tipo de Série) - ex. wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST)
bar("B", "HB"),
pie("P"),
timeline("TL"),
gauge("G"),
line("L", "HL"),
area("A", "HA"),
spline("LS"),
donut("DN"),
halfdonut("HDN"),
scatter("D"),
bolha("BB") ,
histograma("HST");

Título (String) - ex. wChartSeriesListDTO.getChartProperties().setTitle("título")
axisXTitle (String) - ex. wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle")
axisYTitle (String) - ex.
(Corda) - ex. wChartSeriesListDTO.getChartProperties().setAxisY2Title("axisY2Title")

axisXPositionTitle (AxisXPositionTextEnum) - ex. wChartSeriesListDTO.getChartProperties().setAxisXPositionTitle(AxisXPositionTextEnum.OUTER_RIGHT)
INNER_RIGHT("inner-right"),
INNER_CENTER("inner-center"),
INNER_LEFT("inner-left"),
OUTER_RIGHT("outer-right"),
OUTER_CENTER( "centro externo"),
OUTER_LEFT("externo esquerdo");

axisYPositionTitle (AxisYPositionTextEnum) - ex. wChartSeriesListDTO.getChartProperties().setAxisYPositionTitle(AxisYPositionTextEnum.OUTER_TOP)
INNER_TOP("inner-top"),

INNER_MIDDLE("inner-middle"),


OUTER_MIDDLE("meio externo"),
OUTER_BOTTOM("fundo externo");

axisXType (AxisXType) - ex. wChartSeriesListDTO.getChartProperties().setAxisXType(AxisXTypeEnum.TIMESERIES)
TIMESERIES("timeseries"),
CATEGORY("category"),
INDEXED("indexed");

axisYType (AxisYType) - ex. wChartSeriesListDTO.getChartProperties().setAxisYType(AxisYTypeEnum.LINEAR)
LINEAR("linear"),
TIME("time"),
TIMESERIES("timeseries"),
LOG("log");

innerAxisY (Booleano) ex. wChartSeriesListDTO.getChartProperties().setInnerAxisY(true)
innerAxisY2 (Booleano) ex. wChartSeriesListDTO.getChartProperties().
(ArrayList) - ex. wChartSeriesListDTO.getChartProperties().setTickValueAxisX(new ArrayList<>(Arrays.asList("0","10","15","30","40")))
tickValueAxisY ArrayList() - ex. wChartSeriesListDTO.getChartProperties().setTickValueAxisY(new ArrayList<>(Arrays.asList("0","10","15","30","40")))
tickValleyAxisY2 (ArrayList) - ex. wChartSeriesListDTO.getChartProperties().setTickValueAxisY2(new ArrayList<>(Arrays.asList("0","10","15","30","40")))
showGridX (Boolean) ex. wChartSeriesListDTO.getChartProperties().setShowGridX(true)
showGridY (Booleano) ex. wChartSeriesListDTO.getChartProperties().
(WChartGridLineDTO) ex. wChartSeriesListDTO.getChartProperties().setLinesGridX(new ArrayList(Arrays.asList(new WChartGridLineDTO())));
linesGridY (WChartGridLineDTO) ex. wChartSeriesListDTO.getChartProperties().setLinesGridY(new ArrayList(Arrays.asList(new WChartGridLineDTO())));
