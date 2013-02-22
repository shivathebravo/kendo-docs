---
title: stockChart-seriesItem
slug: jsp-stockChart-seriesItem
tags: api, java
publish: true
---

# \<kendo:stockChart-seriesItem\>

Array of series definitions.

#### Example
    <kendo:stockChart-series>
        <kendo:stockChart-seriesItem></kendo:stockChart-seriesItem>
    </kendo:stockChart-series>

## Configuration Attributes

### aggregate `String`

Aggregate function for date series.

#### Example
    <kendo:stockChart-seriesItem aggregate="aggregate">
    </kendo:stockChart-seriesItem>

### axis `String`

The name of the value axis to use.

#### Example
    <kendo:stockChart-seriesItem axis="axis">
    </kendo:stockChart-seriesItem>

### closeField `String`

The data field containing the close value.

#### Example
    <kendo:stockChart-seriesItem closeField="closeField">
    </kendo:stockChart-seriesItem>

### color `String`

The series base color.

#### Example
    <kendo:stockChart-seriesItem color="color">
    </kendo:stockChart-seriesItem>

### colorField `String`

The data field containing the point color.

#### Example
    <kendo:stockChart-seriesItem colorField="colorField">
    </kendo:stockChart-seriesItem>

### dashType `String`

The series line dash type.

#### Example
    <kendo:stockChart-seriesItem dashType="dashType">
    </kendo:stockChart-seriesItem>

### data `Object`

Array of data items. The data item type can be either a:

#### Example
    <kendo:stockChart-seriesItem data="data">
    </kendo:stockChart-seriesItem>

### downColor `String`

The series color when open value is smoller then close value.

#### Example
    <kendo:stockChart-seriesItem downColor="downColor">
    </kendo:stockChart-seriesItem>

### downColorField `String`

The data field containing the body color.

#### Example
    <kendo:stockChart-seriesItem downColorField="downColorField">
    </kendo:stockChart-seriesItem>

### field `String`

The data field containing the series value.

#### Example
    <kendo:stockChart-seriesItem field="field">
    </kendo:stockChart-seriesItem>

### gap `float`

The distance between category clusters.

#### Example
    <kendo:stockChart-seriesItem gap="gap">
    </kendo:stockChart-seriesItem>

### groupNameTemplate `String`

Name template for auto-generated series when binding to grouped data.

#### Example
    <kendo:stockChart-seriesItem groupNameTemplate="groupNameTemplate">
    </kendo:stockChart-seriesItem>

### highField `String`

The data field containing the high value.

#### Example
    <kendo:stockChart-seriesItem highField="highField">
    </kendo:stockChart-seriesItem>

### line `String`

Line options. Further configuration is available via [kendo:stockChart-seriesItem-line](#kendo-stockChart-seriesItem-line). 

#### Example
    <kendo:stockChart-seriesItem line="line">
    </kendo:stockChart-seriesItem>

### lowField `String`

The data field containing the low value.

#### Example
    <kendo:stockChart-seriesItem lowField="lowField">
    </kendo:stockChart-seriesItem>

### missingValues `String`

Configures the behavior for handling missing values.

#### Example
    <kendo:stockChart-seriesItem missingValues="missingValues">
    </kendo:stockChart-seriesItem>

### name `String`

The series name visible in the legend.

#### Example
    <kendo:stockChart-seriesItem name="name">
    </kendo:stockChart-seriesItem>

### opacity `float`

The series opacity.

#### Example
    <kendo:stockChart-seriesItem opacity="opacity">
    </kendo:stockChart-seriesItem>

### openField `String`

The data field containing the open value.

#### Example
    <kendo:stockChart-seriesItem openField="openField">
    </kendo:stockChart-seriesItem>

### spacing `float`

Space between points as proportion of the point width.

#### Example
    <kendo:stockChart-seriesItem spacing="spacing">
    </kendo:stockChart-seriesItem>

### stack `Object`

A value indicating if the series should be stacked. String value indicates that the series should be stacked in a group with the specified name.
Available for column series.

#### Example
    <kendo:stockChart-seriesItem stack="stack">
    </kendo:stockChart-seriesItem>

### type `String`

The type of the series. Available types:

#### Example
    <kendo:stockChart-seriesItem type="type">
    </kendo:stockChart-seriesItem>

### width `float`

The line width.

#### Example
    <kendo:stockChart-seriesItem width="width">
    </kendo:stockChart-seriesItem>


##  Configuration JSP Tags

### kendo:stockChart-seriesItem-border

The border of the points.

More documentation is available at [kendo:stockChart-seriesItem-border](stockchart/seriesitem-border).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-border></kendo:stockChart-seriesItem-border>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-highlight

Configures the appearance of highlighted points.

More documentation is available at [kendo:stockChart-seriesItem-highlight](stockchart/seriesitem-highlight).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-highlight></kendo:stockChart-seriesItem-highlight>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-labels

Configures the series data labels.

More documentation is available at [kendo:stockChart-seriesItem-labels](stockchart/seriesitem-labels).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-labels></kendo:stockChart-seriesItem-labels>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-line

Line options.

More documentation is available at [kendo:stockChart-seriesItem-line](stockchart/seriesitem-line).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-line></kendo:stockChart-seriesItem-line>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-markers

Marker options.

More documentation is available at [kendo:stockChart-seriesItem-markers](stockchart/seriesitem-markers).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-markers></kendo:stockChart-seriesItem-markers>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-overlay

The effects overlay.

More documentation is available at [kendo:stockChart-seriesItem-overlay](stockchart/seriesitem-overlay).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-overlay></kendo:stockChart-seriesItem-overlay>
    </kendo:stockChart-seriesItem>

### kendo:stockChart-seriesItem-tooltip

The data point tooltip configuration options.

More documentation is available at [kendo:stockChart-seriesItem-tooltip](stockchart/seriesitem-tooltip).

#### Example

    <kendo:stockChart-seriesItem>
        <kendo:stockChart-seriesItem-tooltip></kendo:stockChart-seriesItem-tooltip>
    </kendo:stockChart-seriesItem>
