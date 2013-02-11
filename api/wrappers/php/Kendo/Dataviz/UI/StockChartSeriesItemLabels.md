---
title: StockChartSeriesItemLabels
slug: php-dataviz-ui-stockchartseriesitemlabels
tags: api, php
publish: true
---

# \Kendo\Dataviz\UI\StockChartSeriesItemLabels

A PHP class representing the labels setting of StockChartSeriesItem.


## Methods

### background
The background color of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->background('value');
    ?>

### border

The border of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `\Kendo\Dataviz\UI\StockChartSeriesItemLabelsBorder|array`


#### Example - using [\Kendo\Dataviz\UI\StockChartSeriesItemLabelsBorder](/api/wrappers/php/Kendo/Dataviz/UI/StockChartSeriesItemLabelsBorder)
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $border = new \Kendo\Dataviz\UI\StockChartSeriesItemLabelsBorder();
    $color = 'value';
    $border->color($color);
    $labels->border($border);
    ?>

#### Example - using array

    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $color = 'value';
    $labels->border(array('color' => $color));
    ?>

### color
The text color of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->color('value');
    ?>

### font
The font style of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->font('value');
    ?>

### format
The format of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->format('value');
    ?>

### margin
The margin of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `float|`



#### Example  - using float
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->margin(1);
    ?>

### padding
The padding of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `float|`



#### Example  - using float
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->padding(1);
    ?>

### position
Defines the position of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->position('value');
    ?>

### template
The label template. Template variables:

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction`



#### Example  - using string
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->template('value');
    ?>

#### Example  - using \Kendo\JavaScriptFunction
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->template(new \Kendo\JavaScriptFunction('function() { }'));
    ?>

### visible
The visibility of the labels.

#### Returns
`\Kendo\Dataviz\UI\StockChartSeriesItemLabels`

#### Parameters

##### $value `boolean`



#### Example 
    <?php
    $labels = new \Kendo\Dataviz\UI\StockChartSeriesItemLabels();
    $labels->visible(true);
    ?>
