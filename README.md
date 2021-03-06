## Modules

<dl>
<dt><a href="#hakaiCharts.module_parallelCoordinates">parallelCoordinates</a> ⇒ <code>parallelCoordinatesChart</code></dt>
<dd><p>A reusable d3 parallel coordinates generator with statistical coloring</p>
</dd>
<dt><a href="#hakaiCharts.module_scatterplot">scatterplot</a> ⇒ <code>object</code></dt>
<dd><p>A reusable d3 scatterplot generator</p>
</dd>
<dt><a href="#hakaiCharts.module_verticalLine">verticalLine</a> ⇒ <code>object</code></dt>
<dd><p>A reusable d3 vertical line plot generator</p>
</dd>
</dl>

<a name="hakaiCharts.module_parallelCoordinates"></a>

## parallelCoordinates ⇒ <code>parallelCoordinatesChart</code>
A reusable d3 parallel coordinates generator with statistical coloring

**See**: [example](https://cdn.rawgit.com/tayden/hakai-charts/v1.1.1/examples/para_coords_example.html)  
**Author:** Taylor Denouden  

| Param | Type | Description |
| --- | --- | --- |
| parent | <code>String</code> &#124; <code>DOM_node</code> | A dom element to append the chart to |


* [parallelCoordinates](#hakaiCharts.module_parallelCoordinates) ⇒ <code>parallelCoordinatesChart</code>
    * [.width](#hakaiCharts.module_parallelCoordinates+width) ⇒ <code>int</code> &#124; <code>scatterplot</code>
    * [.height](#hakaiCharts.module_parallelCoordinates+height) ⇒ <code>int</code> &#124; <code>scatterplot</code>
    * [.margin](#hakaiCharts.module_parallelCoordinates+margin) ⇒ <code>int</code> &#124; <code>scatterplot</code>
    * [.data](#hakaiCharts.module_parallelCoordinates+data) ⇒ <code>int</code> &#124; <code>scatterplot</code>
    * [.y](#hakaiCharts.module_parallelCoordinates+y) ⇒ <code>object</code> &#124; <code>scatterplot</code>
    * [.yAccessors](#hakaiCharts.module_parallelCoordinates+yAccessors) ⇒ <code>object</code> &#124; <code>scatterplot</code>
    * [.color](#hakaiCharts.module_parallelCoordinates+color) ⇒ <code>object</code> &#124; <code>scatterplot</code>
    * [.colorAccessor](#hakaiCharts.module_parallelCoordinates+colorAccessor) ⇒ <code>object</code> &#124; <code>scatterplot</code>
    * [.onClick](#hakaiCharts.module_parallelCoordinates+onClick) ⇒ <code>object</code> &#124; <code>scatterplot</code>
    * [.render()](#hakaiCharts.module_parallelCoordinates+render) ⇒ <code>parallelCoordinatesChart</code>
    * [.redraw()](#hakaiCharts.module_parallelCoordinates+redraw) ⇒ <code>parallelCoordinatesChart</code>

<a name="hakaiCharts.module_parallelCoordinates+width"></a>

### parallelCoordinates.width ⇒ <code>int</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>int</code> | Value to set width to |

<a name="hakaiCharts.module_parallelCoordinates+height"></a>

### parallelCoordinates.height ⇒ <code>int</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| val | <code>int</code> | 

<a name="hakaiCharts.module_parallelCoordinates+margin"></a>

### parallelCoordinates.margin ⇒ <code>int</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| val | <code>int</code> | 

<a name="hakaiCharts.module_parallelCoordinates+data"></a>

### parallelCoordinates.data ⇒ <code>int</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| val | <code>int</code> | 

<a name="hakaiCharts.module_parallelCoordinates+y"></a>

### parallelCoordinates.y ⇒ <code>object</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| y | <code>object</code> | 

<a name="hakaiCharts.module_parallelCoordinates+yAccessors"></a>

### parallelCoordinates.yAccessors ⇒ <code>object</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| yAccessors | <code>object</code> | 

<a name="hakaiCharts.module_parallelCoordinates+color"></a>

### parallelCoordinates.color ⇒ <code>object</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| color | <code>object</code> | 

<a name="hakaiCharts.module_parallelCoordinates+colorAccessor"></a>

### parallelCoordinates.colorAccessor ⇒ <code>object</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| colorAccessor | <code>object</code> | 

<a name="hakaiCharts.module_parallelCoordinates+onClick"></a>

### parallelCoordinates.onClick ⇒ <code>object</code> &#124; <code>scatterplot</code>
**Kind**: instance property of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  

| Param | Type |
| --- | --- |
| onClick | <code>object</code> | 

<a name="hakaiCharts.module_parallelCoordinates+render"></a>

### parallelCoordinates.render() ⇒ <code>parallelCoordinatesChart</code>
**Kind**: instance method of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  
<a name="hakaiCharts.module_parallelCoordinates+redraw"></a>

### parallelCoordinates.redraw() ⇒ <code>parallelCoordinatesChart</code>
**Kind**: instance method of <code>[parallelCoordinates](#hakaiCharts.module_parallelCoordinates)</code>  
<a name="hakaiCharts.module_scatterplot"></a>

## scatterplot ⇒ <code>object</code>
A reusable d3 scatterplot generator

**Returns**: <code>object</code> - scatterplot chart  
**See**: [example](https://cdn.rawgit.com/tayden/hakai-charts/v1.1.1/examples/scatterplot_example.html)  
**Author:** Taylor Denouden  

| Param | Type | Description |
| --- | --- | --- |
| parent | <code>String</code> &#124; <code>DOM_node</code> | A DOM element to append the chart to |


* [scatterplot](#hakaiCharts.module_scatterplot) ⇒ <code>object</code>
    * [.width](#hakaiCharts.module_scatterplot+width) ⇒ <code>chart</code>
    * [.width](#hakaiCharts.module_scatterplot+width) ⇒ <code>int</code>
    * [.height](#hakaiCharts.module_scatterplot+height) ⇒ <code>chart</code>
    * [.height](#hakaiCharts.module_scatterplot+height) ⇒ <code>int</code>
    * [.margin](#hakaiCharts.module_scatterplot+margin) ⇒ <code>chart</code>
    * [.margin](#hakaiCharts.module_scatterplot+margin) ⇒ <code>Object</code>
    * [.data](#hakaiCharts.module_scatterplot+data) ⇒ <code>chart</code>
    * [.data](#hakaiCharts.module_scatterplot+data) ⇒ <code>Array.&lt;Object&gt;</code>
    * [.xAccessor](#hakaiCharts.module_scatterplot+xAccessor) ⇒ <code>chart</code>
    * [.xAccessor](#hakaiCharts.module_scatterplot+xAccessor) ⇒ <code>function</code> &#124; <code>Number</code>
    * [.yAccessor](#hakaiCharts.module_scatterplot+yAccessor) ⇒ <code>chart</code>
    * [.yAccessor](#hakaiCharts.module_scatterplot+yAccessor) ⇒ <code>function</code> &#124; <code>Number</code>
    * [.xLabel](#hakaiCharts.module_scatterplot+xLabel) ⇒ <code>chart</code>
    * [.xLabel](#hakaiCharts.module_scatterplot+xLabel) ⇒ <code>String</code>
    * [.yLabel](#hakaiCharts.module_scatterplot+yLabel) ⇒ <code>chart</code>
    * [.yLabel](#hakaiCharts.module_scatterplot+yLabel) ⇒ <code>String</code>
    * [.xLog](#hakaiCharts.module_scatterplot+xLog) ⇒ <code>chart</code>
    * [.xLog](#hakaiCharts.module_scatterplot+xLog) ⇒ <code>Boolean</code>
    * [.yLog](#hakaiCharts.module_scatterplot+yLog) ⇒ <code>chart</code>
    * [.yLog](#hakaiCharts.module_scatterplot+yLog) ⇒ <code>Boolean</code>
    * [.color](#hakaiCharts.module_scatterplot+color) ⇒ <code>chart</code>
    * [.color](#hakaiCharts.module_scatterplot+color) ⇒ <code>function</code>
    * [.colorAccessor](#hakaiCharts.module_scatterplot+colorAccessor) ⇒ <code>chart</code>
    * [.colorAccessor](#hakaiCharts.module_scatterplot+colorAccessor) ⇒ <code>function</code>
    * [.keyAccessor](#hakaiCharts.module_scatterplot+keyAccessor) ⇒ <code>chart</code>
    * [.keyAccessor](#hakaiCharts.module_scatterplot+keyAccessor) ⇒ <code>int</code>
    * [.radius](#hakaiCharts.module_scatterplot+radius) ⇒ <code>chart</code>
    * [.radius](#hakaiCharts.module_scatterplot+radius) ⇒ <code>int</code> &#124; <code>function</code>
    * [.rSquared](#hakaiCharts.module_scatterplot+rSquared) ⇒ <code>float</code>
    * [.correlation](#hakaiCharts.module_scatterplot+correlation) ⇒ <code>float</code>
    * [.covariance](#hakaiCharts.module_scatterplot+covariance) ⇒ <code>float</code>
    * [.render()](#hakaiCharts.module_scatterplot+render) ⇒ <code>chart</code>
    * [.redraw()](#hakaiCharts.module_scatterplot+redraw) ⇒ <code>chart</code>

<a name="hakaiCharts.module_scatterplot+width"></a>

### scatterplot.width ⇒ <code>chart</code>
Set the width attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>int</code> | The chart width |

<a name="hakaiCharts.module_scatterplot+width"></a>

### scatterplot.width ⇒ <code>int</code>
Get the width attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+height"></a>

### scatterplot.height ⇒ <code>chart</code>
Set the height attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>int</code> | The chart height |

<a name="hakaiCharts.module_scatterplot+height"></a>

### scatterplot.height ⇒ <code>int</code>
Get the height attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+margin"></a>

### scatterplot.margin ⇒ <code>chart</code>
Set the margin attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>Object</code> | The chart margins in format {top: 5, left: 5, right: 10, bottom: 15} |

<a name="hakaiCharts.module_scatterplot+margin"></a>

### scatterplot.margin ⇒ <code>Object</code>
Get the margin attribute of a chart.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+data"></a>

### scatterplot.data ⇒ <code>chart</code>
Set the data that accessor functions refer to.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>Array.&lt;Object&gt;</code> | JSON data being accessed by all accessor functions |

<a name="hakaiCharts.module_scatterplot+data"></a>

### scatterplot.data ⇒ <code>Array.&lt;Object&gt;</code>
Get the data that accessor functions refer to.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+xAccessor"></a>

### scatterplot.xAccessor ⇒ <code>chart</code>
Set the function used to access the data shown on the x axis.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>function</code> &#124; <code>Number</code> | The x axis data accessor function |

<a name="hakaiCharts.module_scatterplot+xAccessor"></a>

### scatterplot.xAccessor ⇒ <code>function</code> &#124; <code>Number</code>
Get the function used to access the data shown on the x axis.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
**Returns**: <code>function</code> &#124; <code>Number</code> - The x axis data accessor  
<a name="hakaiCharts.module_scatterplot+yAccessor"></a>

### scatterplot.yAccessor ⇒ <code>chart</code>
Set the function used to access the data shown on the y axis.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>function</code> &#124; <code>Number</code> | The y axis data accessor function |

<a name="hakaiCharts.module_scatterplot+yAccessor"></a>

### scatterplot.yAccessor ⇒ <code>function</code> &#124; <code>Number</code>
Get the function used to access the data shown on the y axis.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
**Returns**: <code>function</code> &#124; <code>Number</code> - The y axis data accessor  
<a name="hakaiCharts.module_scatterplot+xLabel"></a>

### scatterplot.xLabel ⇒ <code>chart</code>
Set the x axis label.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>String</code> | The x label |

<a name="hakaiCharts.module_scatterplot+xLabel"></a>

### scatterplot.xLabel ⇒ <code>String</code>
Get the x axis label.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+yLabel"></a>

### scatterplot.yLabel ⇒ <code>chart</code>
Set the y axis label.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>String</code> | The y label |

<a name="hakaiCharts.module_scatterplot+yLabel"></a>

### scatterplot.yLabel ⇒ <code>String</code>
Get the y axis label.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+xLog"></a>

### scatterplot.xLog ⇒ <code>chart</code>
Set the x axis scale as log transformed or not.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>Boolean</code> | <code>false</code> | Flag to transform x axis |

<a name="hakaiCharts.module_scatterplot+xLog"></a>

### scatterplot.xLog ⇒ <code>Boolean</code>
Get boolean of whether the x axis scale is log transformed.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+yLog"></a>

### scatterplot.yLog ⇒ <code>chart</code>
Set the y axis scale as log transformed or not.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>Boolean</code> | <code>false</code> | Flag to transform y axis |

<a name="hakaiCharts.module_scatterplot+yLog"></a>

### scatterplot.yLog ⇒ <code>Boolean</code>
Get boolean of whether the y axis scale is log transformed.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+color"></a>

### scatterplot.color ⇒ <code>chart</code>
Set the color scale function that accepts a data value and returns a color.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>function</code> | <code>schemeCategory10</code> | The color scale function |

<a name="hakaiCharts.module_scatterplot+color"></a>

### scatterplot.color ⇒ <code>function</code>
Get the color scale function

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+colorAccessor"></a>

### scatterplot.colorAccessor ⇒ <code>chart</code>
Set the function used to access the data and pass the value to the color function.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>function</code> | <code>function(){ return 0; }</code> | The colorAccessor function |

<a name="hakaiCharts.module_scatterplot+colorAccessor"></a>

### scatterplot.colorAccessor ⇒ <code>function</code>
Get the function used to access the data point color.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+keyAccessor"></a>

### scatterplot.keyAccessor ⇒ <code>chart</code>
Set a function used to determine which points shown are the same data point.
Allows for mark translation on redraw.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>function</code> | <code>function(d){ return d.key; }</code> | The keyAccessor function |

<a name="hakaiCharts.module_scatterplot+keyAccessor"></a>

### scatterplot.keyAccessor ⇒ <code>int</code>
Get the function used to determine which points shown are the same datum.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+radius"></a>

### scatterplot.radius ⇒ <code>chart</code>
Set the radius value of the scatterplot

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>Number</code> | <code>5</code> | The radius in px |

<a name="hakaiCharts.module_scatterplot+radius"></a>

### scatterplot.radius ⇒ <code>int</code> &#124; <code>function</code>
Get the radius value of the scatterplot

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+rSquared"></a>

### scatterplot.rSquared ⇒ <code>float</code>
Return the R squared value determined by the linear regression function.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+correlation"></a>

### scatterplot.correlation ⇒ <code>float</code>
Return the correlation value determined by the linear regression function.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+covariance"></a>

### scatterplot.covariance ⇒ <code>float</code>
Return the covariance value determined by the linear regression function.

**Kind**: instance property of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+render"></a>

### scatterplot.render() ⇒ <code>chart</code>
Draw the chart after parameters have been set.

**Kind**: instance method of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_scatterplot+redraw"></a>

### scatterplot.redraw() ⇒ <code>chart</code>
Redraw and transform the chart after parameter changes.

**Kind**: instance method of <code>[scatterplot](#hakaiCharts.module_scatterplot)</code>  
<a name="hakaiCharts.module_verticalLine"></a>

## verticalLine ⇒ <code>object</code>
A reusable d3 vertical line plot generator

**Returns**: <code>object</code> - verticalLine chart  
**See**: [example](https://cdn.rawgit.com/tayden/hakai-charts/v1.1.1/examples/vertical_line_example.html)  
**Author:** Taylor Denouden  

| Param | Type | Description |
| --- | --- | --- |
| parent | <code>String</code> &#124; <code>DOM_node</code> | A DOM element to append the chart to |


* [verticalLine](#hakaiCharts.module_verticalLine) ⇒ <code>object</code>
    * [.margin](#hakaiCharts.module_verticalLine+margin) ⇒ <code>chart</code>
    * [.margin](#hakaiCharts.module_verticalLine+margin) ⇒ <code>Object</code>
    * [.margin2](#hakaiCharts.module_verticalLine+margin2) ⇒ <code>chart</code>
    * [.margin2](#hakaiCharts.module_verticalLine+margin2) ⇒ <code>Object</code>
    * [.width](#hakaiCharts.module_verticalLine+width) ⇒ <code>chart</code>
    * [.width](#hakaiCharts.module_verticalLine+width) ⇒ <code>int</code>
    * [.height](#hakaiCharts.module_verticalLine+height) ⇒ <code>chart</code>
    * [.height](#hakaiCharts.module_verticalLine+height) ⇒ <code>int</code>
    * [.data](#hakaiCharts.module_verticalLine+data) ⇒ <code>chart</code>
    * [.data](#hakaiCharts.module_verticalLine+data) ⇒ <code>Array.&lt;Object&gt;</code>
    * [.keyAccessor](#hakaiCharts.module_verticalLine+keyAccessor) ⇒ <code>chart</code>
    * [.keyAccessor](#hakaiCharts.module_verticalLine+keyAccessor) ⇒ <code>int</code>
    * [.xAccessor](#hakaiCharts.module_verticalLine+xAccessor) ⇒ <code>chart</code>
    * [.xAccessor](#hakaiCharts.module_verticalLine+xAccessor) ⇒ <code>function</code> &#124; <code>Number</code>
    * [.xAccessor](#hakaiCharts.module_verticalLine+xAccessor) ⇒ <code>chart</code>
    * [.xAccessor](#hakaiCharts.module_verticalLine+xAccessor) ⇒ <code>function</code> &#124; <code>Number</code>
    * [.yAccessor](#hakaiCharts.module_verticalLine+yAccessor) ⇒ <code>chart</code>
    * [.yAccessor](#hakaiCharts.module_verticalLine+yAccessor) ⇒ <code>function</code> &#124; <code>Number</code>
    * [.yLabel](#hakaiCharts.module_verticalLine+yLabel) ⇒ <code>chart</code>
    * [.yLabel](#hakaiCharts.module_verticalLine+yLabel) ⇒ <code>String</code>
    * [.xLabel](#hakaiCharts.module_verticalLine+xLabel) ⇒ <code>chart</code>
    * [.xLabel](#hakaiCharts.module_verticalLine+xLabel) ⇒ <code>String</code>
    * [.redraw()](#hakaiCharts.module_verticalLine+redraw) ⇒ <code>chart</code>
    * [.render()](#hakaiCharts.module_verticalLine+render) ⇒ <code>chart</code>

<a name="hakaiCharts.module_verticalLine+margin"></a>

### verticalLine.margin ⇒ <code>chart</code>
Set the margin attribute of the focus chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>Object</code> | The chart margins in format {top: 5, left: 5, right: 10, bottom: 15} |

<a name="hakaiCharts.module_verticalLine+margin"></a>

### verticalLine.margin ⇒ <code>Object</code>
Get the margin attribute of the focus chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+margin2"></a>

### verticalLine.margin2 ⇒ <code>chart</code>
Set the margin2 attribute of the context chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>Object</code> | The chart margins in format {top: 5, left: 5, right: 10, bottom: 15} |

<a name="hakaiCharts.module_verticalLine+margin2"></a>

### verticalLine.margin2 ⇒ <code>Object</code>
Get the margin attribute of the context chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+width"></a>

### verticalLine.width ⇒ <code>chart</code>
Set the width attribute of a chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>int</code> | The chart width |

<a name="hakaiCharts.module_verticalLine+width"></a>

### verticalLine.width ⇒ <code>int</code>
Get the width attribute of a chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+height"></a>

### verticalLine.height ⇒ <code>chart</code>
Set the height attribute of a chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>int</code> | The chart height |

<a name="hakaiCharts.module_verticalLine+height"></a>

### verticalLine.height ⇒ <code>int</code>
Get the height attribute of a chart.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+data"></a>

### verticalLine.data ⇒ <code>chart</code>
Set the data that accessor functions refer to.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>Array.&lt;Object&gt;</code> | JSON data being accessed by all accessor functions |

<a name="hakaiCharts.module_verticalLine+data"></a>

### verticalLine.data ⇒ <code>Array.&lt;Object&gt;</code>
Get the data that accessor functions refer to.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+keyAccessor"></a>

### verticalLine.keyAccessor ⇒ <code>chart</code>
Set a function used to determine which points shown are the same data point.
Allows for mark translation on redraw.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [val] | <code>function</code> | <code>function(d){ return d.key; }</code> | The keyAccessor function |

<a name="hakaiCharts.module_verticalLine+keyAccessor"></a>

### verticalLine.keyAccessor ⇒ <code>int</code>
Get the function used to determine which points shown are the same datum.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+xAccessor"></a>

### verticalLine.xAccessor ⇒ <code>chart</code>
Set the function used to access the data shown in the tooltip.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>function</code> &#124; <code>Number</code> | The tooltip value data accessor function |

<a name="hakaiCharts.module_verticalLine+xAccessor"></a>

### verticalLine.xAccessor ⇒ <code>function</code> &#124; <code>Number</code>
Get the function used to access the data shown in the tooltip.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
**Returns**: <code>function</code> &#124; <code>Number</code> - The tooltip value data accessor  
<a name="hakaiCharts.module_verticalLine+xAccessor"></a>

### verticalLine.xAccessor ⇒ <code>chart</code>
Set the function used to access the data shown on the x axis.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>function</code> &#124; <code>Number</code> | The x axis data accessor function |

<a name="hakaiCharts.module_verticalLine+xAccessor"></a>

### verticalLine.xAccessor ⇒ <code>function</code> &#124; <code>Number</code>
Get the function used to access the data shown on the x axis.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
**Returns**: <code>function</code> &#124; <code>Number</code> - The x axis data accessor  
<a name="hakaiCharts.module_verticalLine+yAccessor"></a>

### verticalLine.yAccessor ⇒ <code>chart</code>
Set the function used to access the data shown on the y axis.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>function</code> &#124; <code>Number</code> | The y axis data accessor function |

<a name="hakaiCharts.module_verticalLine+yAccessor"></a>

### verticalLine.yAccessor ⇒ <code>function</code> &#124; <code>Number</code>
Get the function used to access the data shown on the y axis.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
**Returns**: <code>function</code> &#124; <code>Number</code> - The y axis data accessor  
<a name="hakaiCharts.module_verticalLine+yLabel"></a>

### verticalLine.yLabel ⇒ <code>chart</code>
Set the y axis label.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>String</code> | The y label |

<a name="hakaiCharts.module_verticalLine+yLabel"></a>

### verticalLine.yLabel ⇒ <code>String</code>
Get the y axis label.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+xLabel"></a>

### verticalLine.xLabel ⇒ <code>chart</code>
Set the x axis label.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  

| Param | Type | Description |
| --- | --- | --- |
| [val] | <code>String</code> | The x label |

<a name="hakaiCharts.module_verticalLine+xLabel"></a>

### verticalLine.xLabel ⇒ <code>String</code>
Get the x axis label.

**Kind**: instance property of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+redraw"></a>

### verticalLine.redraw() ⇒ <code>chart</code>
Redraw and transform the chart after parameter changes.

**Kind**: instance method of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
<a name="hakaiCharts.module_verticalLine+render"></a>

### verticalLine.render() ⇒ <code>chart</code>
Draw the chart after parameters have been set.

**Kind**: instance method of <code>[verticalLine](#hakaiCharts.module_verticalLine)</code>  
