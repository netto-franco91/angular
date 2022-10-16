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
**There is an enum with the types available to the user: br/com/philips/tasy/dto/shared/wchart/SerieType.java**<br>
bar("B", "HB"),<br>
pie("P"),<br>
timeline("TL"),<br>
gauge("G"),<br>
line("L", "HL"),<br>
area("A", "HA"),<br>
spline("LS"),<br>
donut("DN"),<br>
halfdonut("HDN"),<br>
scatter("D"),<br>
bubble("BB"),<br>
histogram("HST");<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST);
```
**Title (field type String) - this attribute allows the user to set the title for the chart**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTitle("title");
```
**axisXTitle (field type String) - this attribute allows the user to set the title for the axis X**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle");
```
**axisYTitle (field type String) - this attribute allows the user to set the title for the axis Y**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYTitle("axisYTitle");
```
**axisY2Title (field type String) - this attribute allows the user to set the title for the axis Y2**<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisY2Title("axisY2Title");
```
