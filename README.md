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
**minTargetValue (field type String) - this attribute allows the user to set the minimum target value**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetValue("minTargetValue");
```
**ieTargetType (field type String) - this attribute allows the user to set the type of the target**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setIeTargetType("ieTargetType");
```
**StringType (field type String) - this attribute allows the user to set the type of the string**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setStringType("stringType");
```
**Type (field type SerieType) - this attribute allows the user to set the type of the chart serie**<br>
**There is an enum with the types available to the user:
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
bubble("BB"),
histogram("HST");**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setStringType("stringType");
```




Type (SerieType) - ex. wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST)
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
bubble("BB"),
histogram("HST");

Title (String) - ex. wChartSeriesListDTO.getChartProperties().setTitle("title")
axisXTitle (String) - ex. wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle")
axisYTitle (String) - ex. wChartSeriesListDTO.getChartProperties().setAxisYTitle("axisYTitle")
axisY2Title (String) - ex. wChartSeriesListDTO.getChartProperties().setAxisY2Title("axisY2Title")
