- **maxTargetField (field type String)** <br>
#### :page_with_curl: Description
this attribute allows the user to set the maximum target field<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java
wChartSeriesListDTO.getChartProperties().setMaxTargetField("maxTargetField");
```
- **minTargetField (field type String)** - this attribute allows the user to set the minimum target field<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetField("minTargetField");
```
- **maxTargetValue (field type String)** - this attribute allows the user to set the maximum target value<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMaxTargetValue("maxTargetValue");
```
- **minTargetValue (field type String)** - this attribute allows the user to set the minimum target value<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setMinTargetValue("minTargetValue");
```
- **ieTargetType (field type String)** - this attribute allows the user to set the type of the target<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
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

  **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setSerieType(SerieType.HST);
```
- **Title (field type String)** - this attribute allows the user to set the title for the chart<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTitle("title");
```
- **axisXTitle (field type String)** - this attribute allows the user to set the title for the axis X<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXTitle("axisXTitle");
```
- **axisYTitle (field type String)** - this attribute allows the user to set the title for the axis Y<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYTitle("axisYTitle");
```
- **axisY2Title (field type String)** - this attribute allows the user to set the title for the axis Y2<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
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
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXPositionTitle(AxisXPositionTextEnum.OUTER_RIGHT);
```
- **axisYPositionTitle  (field type AxisYPositionTextEnum)** - this attribute allows the user to define the position of the Y axis title<br>
  **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisYPositionTextEnum.java**<br> 
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
- **axisXType  (field type AxisXType)** - this attribute allows the user to define the type of the X axis<br>
  **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisXTypeEnum.java**<br> 
TIMESERIES("timeseries")<br>
CATEGORY("category")<br>
INDEXED("indexed")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisXType(AxisXTypeEnum.TIMESERIES);
```
- **axisYType  (field type AxisYType)** - this attribute allows the user to define the type of the Y axis<br>
  **There is an enum with the positions available to the user: br/com/philips/tasy/dto/shared/wchart/AxisYTypeEnum.java**<br> 
LINEAR("linear")<br>
TIME("time")<br>
TIMESERIES("timeseries")<br>
LOG("log")<br>
 **In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setAxisYType(AxisYTypeEnum.LINEAR);
```
- **innerAxisY (field type Boolean)** - this attribute allows the user define if want to set the inner axis Y<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setInnerAxisY(true);
```
- **innerAxisY2 (field type Boolean)** - this attribute allows the user define if want to set the inner axis Y2<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setInnerAxisY2(true);
```
- **tickValueAxisX (field type ArrayList)** - this attribute allows the user to tick values for axis X<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisX(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
- **tickValueAxisY (field type ArrayList)** - this attribute allows the user to tick values for axis Y<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisY(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
- **tickValueAxisY2 (field type ArrayList)** - this attribute allows the user to tick values for axis Y2<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisY2(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
- **tickValueAxisY2 (field type ArrayList)** - this attribute allows the user to tick values for axis Y2<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setTickValueAxisY2(new ArrayList<>(Arrays.asList("0","10","15","30","40")));
```
- **showGridX (field type Boolean)** - this attribute allows the user define if want to show the grid´s at the axis X<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setShowGridX(true);
```
- **showGridY (field type Boolean)** - this attribute allows the user define if want to show the grid´s at the axis Y<br>
**In the backend the user can set this propierty**
#### :pencil2: Example
```java I'm tab B
wChartSeriesListDTO.getChartProperties().setShowGridY(true);
```
- **linesGridX (WChartGridLineDTO)** - this attribute allows the user define if want to set and show the lines at the axis X<br>
- **linesGridY (WChartGridLineDTO)** - this attribute allows the user define if want to set and show the lines at the axis Y<br>
**In the backend the user can create a method to fill X axis lines array and Y axis lines array**
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
