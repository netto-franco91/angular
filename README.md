# Properties to configure the chart and its axes from the Backend:<br><br>

**maxTargetField** <br>
#### :page_with_curl: Description
this attribute allows the user to set the maximum target field<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java
wChartSeriesListDTO.getChartProperties().setMaxTargetField("maxTargetField");
```
----
**minTargetField**<br> 
#### :page_with_curl: Description
this attribute allows the user to set the minimum target field<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetField("minTargetField");
```
----
**maxTargetValue**<br>
#### :page_with_curl: Description
this attribute allows the user to set the maximum target value<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMaxTargetValue("maxTargetValue");
```
----
**minTargetValue**<br>
#### :page_with_curl: Description
this attribute allows the user to set the minimum target value<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetValue("minTargetValue");
```
----
**ieTargetType**<br>
#### :page_with_curl: Description
this attribute allows the user to set the type of the target<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setIeTargetType("ieTargetType");
```
----
**StringType**<br>
#### :page_with_curl: Description
this attribute allows the user to set the type of the string<br>
data type the property accepts - String<br>
<br>**In the backend the user can set the same as the example:**
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setStringType("stringType");
```
----
**Type**<br>
#### :page_with_curl: Description
this attribute allows the user to set the type of the chart serie<br>
data type the property accepts - SerieType<br>
<br> - **There is an enum with the types available to the user: br/com/philips/tasy/dto/shared/wchart/SerieType.java**<br>
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

  **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST);
```
----
**Title**<br>
#### :page_with_curl: Description
this attribute allows the user to set the title for the chart<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTitle("title");
```
----
**axisXTitle**<br>
#### :page_with_curl: Description
this attribute allows the user to set the title for the axis X<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle");
```
----
**axisYTitle**<br>
#### :page_with_curl: Description
this attribute allows the user to set the title for the axis Y<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYTitle("axisYTitle");
```
----
**axisY2Title**<br>
#### :page_with_curl: Description
this attribute allows the user to set the title for the axis Y2<br>
data type the property accepts - String<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisY2Title("axisY2Title");
```
----
**axisXPositionTitle**<br>
#### :page_with_curl: Description
this attribute allows the user to define the position of the X axis title<br>
data type the property accepts - AxisXPositionTextEnum<br>
  <br> - **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisXPositionTextEnum.java**<br> 
INNER_RIGHT("inner-right")<br>
INNER_CENTER("inner-center")<br>
INNER_LEFT("inner-left")<br>
OUTER_RIGHT("outer-right")<br>
OUTER_CENTER("outer-center")<br>
OUTER_LEFT("outer-left")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXPositionTitle(AxisXPositionTextEnum.OUTER_RIGHT);
```
----
**axisYPositionTitle**<br>
#### :page_with_curl: Description
this attribute allows the user to define the position of the Y axis title<br>
data type the property accepts - AxisYPositionTextEnum<br>
  <br> - **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisYPositionTextEnum.java**<br> 
INNER_TOP("inner-top")<br>
INNER_MIDDLE("inner-middle")<br>
INNER_BOTTOM("inner-bottom")<br>
OUTER_TOP("outer-top")<br>
OUTER_MIDDLE("outer-middle")<br>
OUTER_BOTTOM("outer-bottom")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYPositionTitle(AxisYPositionTextEnum.OUTER_TOP);
```
----
**axisXType**<br>
#### :page_with_curl: Description
this attribute allows the user to define the type of the X axis<br>
data type the property accepts - AxisXType<br>
  <br> - **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisXTypeEnum.java**<br> 
TIMESERIES("timeseries")<br>
CATEGORY("category")<br>
INDEXED("indexed")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXType(AxisXTypeEnum.TIMESERIES);
```
----
**axisYType**<br>
#### :page_with_curl: Description
this attribute allows the user to define the type of the Y axis<br>
data type the property accepts - AxisYType<br>
  <br> - **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisYTypeEnum.java**<br> 
LINEAR("linear")<br>
TIME("time")<br>
TIMESERIES("timeseries")<br>
LOG("log")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYType(AxisYTypeEnum.LINEAR);
```
----
**innerAxisY**<br>
#### :page_with_curl: Description
this attribute allows the user define if want to set the inner axis Y<br>
data type the property accepts - Boolean<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setInnerAxisY(true);
```
----
**innerAxisY2**<br>
#### :page_with_curl: Description
this attribute allows the user define if want to set the inner axis Y2<br>
data type the property accepts - Boolean<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setInnerAxisY2(true);
```
----
**tickValueAxisX**<br>
#### :page_with_curl: Description
this attribute allows the user to tick values for axis X<br>
data type the property accepts - ArrayList<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisX(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
----
**tickValueAxisY**<br>
#### :page_with_curl: Description
this attribute allows the user to tick values for axis Y<br>
data type the property accepts - ArrayList<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisY(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
----
**tickValueAxisY2**<br>
#### :page_with_curl: Description
this attribute allows the user to tick values for axis Y2<br>
data type the property accepts - ArrayList<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisY2(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
----
**showGridX**<br>
#### :page_with_curl: Description
this attribute allows the user define if want to show the grid´s at the axis X<br>
data type the property accepts - Boolean<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setShowGridX(true);
```
----
**showGridY**<br>
#### :page_with_curl: Description
this attribute allows the user define if want to show the grid´s at the axis Y<br>
data type the property accepts - Boolean<br>
<br>**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setShowGridY(true);
```
----
**linesGridX (WChartGridLineDTO)**<br>
#### :page_with_curl: Description
this attribute allows the user define if want to set and show the lines at the axis X<br>
data type the property accepts - (WChartGridLineDTO)<br>
<br> **linesGridY (WChartGridLineDTO)**
#### :page_with_curl: Description
this attribute allows the user define if want to set and show the lines at the axis Y<br>
data type the property accepts - (WChartGridLineDTO)<br>
<br>**In the backend the user can create a method to fill X axis lines array and Y axis lines array**
#### :pencil2: Example
```java I'm tab B
 private void fillArrayLines(ArrayList<WChartGridLineDTO> arrayListLinesX, ArrayList<WChartGridLineDTO> arrayListLinesY) {
  
  // X Lines//
  WChartGridLineDTO wChartGridLineDTOX1 = new WChartGridLineDTO();
        wChartGridLineDTOX1.setCssClass("class1");
        wChartGridLineDTOX1.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOX1.setText("LINE1");
        wChartGridLineDTOX1.setValue(0);

        WChartGridLineDTO wChartGridLineDTOX2 = new WChartGridLineDTO();
        wChartGridLineDTOX2.setCssClass("class1");
        wChartGridLineDTOX2.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOX2.setText("LINE2");
        wChartGridLineDTOX2.setValue(5);

        WChartGridLineDTO wChartGridLineDTOX3 = new WChartGridLineDTO();
        wChartGridLineDTOX3.setCssClass("class1");
        wChartGridLineDTOX3.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOX3.setText("LINE3");
        wChartGridLineDTOX3.setValue(10);
        
        arrayListLinesX.add(wChartGridLineDTOX1);
        arrayListLinesX.add(wChartGridLineDTOX2);
        arrayListLinesX.add(wChartGridLineDTOX3);
        
    // Y Lines// 
    WChartGridLineDTO wChartGridLineDTOY1 = new WChartGridLineDTO();
        wChartGridLineDTOY1.setCssClass("class2");
        wChartGridLineDTOY1.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOY1.setText("LINE1");
        wChartGridLineDTOY1.setValue(45);
        
        WChartGridLineDTO wChartGridLineDTOY2 = new WChartGridLineDTO();
        wChartGridLineDTOY2.setCssClass("class2");
        wChartGridLineDTOY2.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOY2.setText("LINE2");
        wChartGridLineDTOY2.setValue(55);

        WChartGridLineDTO wChartGridLineDTOY3 = new WChartGridLineDTO();
        wChartGridLineDTOY3.setCssClass("class2");
        wChartGridLineDTOY3.setPosition(GridAxesPositionTextEnum.END);
        wChartGridLineDTOY3.setText("LINE3");
        wChartGridLineDTOY3.setValue(66);
        
        arrayListLinesY.add(wChartGridLineDTOY1);
        arrayListLinesY.add(wChartGridLineDTOY2);
        arrayListLinesY.add(wChartGridLineDTOY3);
 };
```
   **Then the user can call the fillArrayLines method**<br>
#### :pencil2: Example
```java I'm tab B
private void callArrayLines(wChartSeriesListDTO) {
        ArrayList<WChartGridLineDTO> arrayListLinesY = new ArrayList<>();
        ArrayList<WChartGridLineDTO> arrayListLinesX = new ArrayList<>();
        fillArrayLines(arrayListLinesX, arrayListLinesY);
        wChartSeriesListDTO.getChartProperties().setLinesGridX(arrayListLinesX);
        wChartSeriesListDTO.getChartProperties().setLinesGridY(arrayListLinesY);
```

# Evolution Chart <br>
In the evolution graph, it is necessary to transform the values, when the X-axis ruler is for years, to render the graph correctly.<br><br>
**Example:** <br>
if the month is 1 (January), it is necessary to transform it to 0.333..., to month placement is correct.<br>
To activate the rules mode on the x-axis, it is necessary to pass 2 parameters, one of which is mandatory, 
<br>
valueX => valueX / 3; || valueX => (valueX / 12) * 4;<br>

**yearFinalScaleTickAxisX**<br>
#### :page_with_curl: Description
this parameter is necessary to know until what year the scale must be created (mandatory for active the ruler)<br>
data type the property accepts - (WChartGridLineDTO)<br>
#### :pencil2: Example<br>
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setYearFinalRulerTickAxisX(19);
```
------
**yearInitialScaleTickAxisX**<br>
#### :page_with_curl: Description
this parameter is used to say in which year it will start the axis scale, if the parameter is not passed, it will start at 0<br>
data type the property accepts - (WChartGridLineDTO)<br>
#### :pencil2: Example<br>
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setYearInitialRulerTickAxisX(5);
```
