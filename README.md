- **maxTargetField (field type String)** - this attribute allows the user to set the maximum target field<br>
**In the backend the user can set the same as the example:**
```java
wChartSeriesListDTO.getChartProperties().setMaxTargetField("maxTargetField");
```
- **minTargetField (field type String)** - this attribute allows the user to set the minimum target field<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetField("minTargetField");
```
- **maxTargetValue (field type String)** - this attribute allows the user to set the maximum target value<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMaxTargetValue("maxTargetValue");
```
- **minTargetValue (field type String)** - this attribute allows the user to set the minimum target value<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetValue("minTargetValue");
```
- **ieTargetType (field type String)** - this attribute allows the user to set the type of the target<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setIeTargetType("ieTargetType");
```
- **StringType (field type String)** - this attribute allows the user to set the type of the string<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setStringType("stringType");
```
- **Type (field type SerieType)** - this attribute allows the user to set the type of the chart serie<br>
**There is an enum with the types available to the user: br/com/philips/tasy/dto/shared/wchart/SerieType.java**<br>
bar("B", "HB")<br>
pie("P") 
timeline("TL")<br>
bar("B", "HB")<br> 
pie("P")<br> 
timeline("TL")<br> 
gauge("G")<br>
line("L", "HL")<br> 
area("A", "HA")<br> 
spline("LS")<br> 
donut("DN")<br> 
halfdonut("HDN")<br> 
scatter("D")<br> 
bubble("BB")<br>
histogram("HST") 

  **In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST);
```
- **Title (field type String)** - this attribute allows the user to set the title for the chart<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTitle("title");
```
- **axisXTitle (field type String)** - this attribute allows the user to set the title for the axis X<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle");
```
- **axisYTitle (field type String)** - this attribute allows the user to set the title for the axis Y<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYTitle("axisYTitle");
```
- **axisY2Title (field type String)** - this attribute allows the user to set the title for the axis Y2<br>
**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisY2Title("axisY2Title");
```

- **axisXPositionTitle (field type AxisXPositionTextEnum)** - this attribute allows the user to define the position of the X axis title<br>
  **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisXPositionTextEnum.java**<br> 
INNER_RIGHT("inner-right")<br>
INNER_CENTER("inner-center")<br>
INNER_LEFT("inner-left")<br>
OUTER_RIGHT("outer-right")<br>
OUTER_CENTER("outer-center")<br>
OUTER_LEFT("outer-left")<br>
 **In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXPositionTitle(AxisXPositionTextEnum.OUTER_RIGHT);
```
- **axisYPositionTitle  (field type AxisYPositionTextEnum)** - this attribute allows the user to define the position of the Y axis title<br>
  **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisYPositionTextEnum.class**<br> 
INNER_TOP("inner-top")<br>
INNER_MIDDLE("inner-middle")<br>
INNER_BOTTOM("inner-bottom")<br>
OUTER_TOP("outer-top")<br>
OUTER_MIDDLE("outer-middle")<br>
OUTER_BOTTOM("outer-bottom")<br>
 **In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYPositionTitle(AxisYPositionTextEnum.OUTER_TOP);
```
