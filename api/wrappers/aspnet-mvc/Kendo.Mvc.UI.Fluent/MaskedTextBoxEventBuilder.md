---
title:MaskedTextBoxEventBuilder
slug:aspnetmvc-kendo.mvc.ui.fluent.maskedtextboxeventbuilder
publish:true
---

# Kendo.Mvc.UI.Fluent.MaskedTextBoxEventBuilder
Defines the fluent interface for configuring the NumericTextBox events.



## Methods

### Change(`System.Func<System.Object,System.Object>`)
Defines the inline handler of the Change client-side event

For additional information check the [change](/kendo-ui/api/web/maskedtextbox#events-change) event documentation.


#### Parameters

##### handler `System.Func<System.Object,System.Object>`
The handler code wrapped in a text tag (Razor syntax).




#### Example (ASPX)
    @(Html.Kendo().MaskedTextBox()
        .Name("MaskedTextBox")
        .Events(events => events.Change(
                @<text>
                    function(e) {
                    //event handling code
                    }
                    </text>
                    ))
                )


### Change(`System.String`)
Defines the name of the JavaScript function that will handle the the Change client-side event.

For additional information check the [change](/kendo-ui/api/web/maskedtextbox#events-change) event documentation.


#### Parameters

##### handler `System.String`
The name of the JavaScript function that will handle the event.




#### Example (ASPX)
    @(Html.Kendo().MaskedTextBox()
        .Name("MaskedTextBox")
        .Events(events => events.Change("change"))
    )



