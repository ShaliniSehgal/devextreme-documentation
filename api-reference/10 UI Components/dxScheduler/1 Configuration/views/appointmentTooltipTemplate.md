---
id: dxScheduler.Options.views.appointmentTooltipTemplate
type: template
default: 'appointmentTooltip'
---
---
##### shortDescription
Specifies a custom template for tooltips displayed when users click an appointment or [cell overflow indicator](/concepts/05%20Widgets/Scheduler/030%20Appointments/080%20Cell%20Overflow%20Indicator.md '/Documentation/Guide/UI_Components/Scheduler/Appointments/Cell_Overflow_Indicator/') in this view.

##### param(model): Object
The data of the appointment for which the tooltip is displayed.

##### field(model.appointmentData): Object
The appointment's data object.

##### field(model.targetedAppointmentData): Object
<!-- %field(model.targetedAppointmentData)% -->

##### param(itemIndex): Number
The appointment's index.

##### param(contentElement): dxElement
#include common-ref-elementparam with { element: "appointment tooltip" }

##### return: String | Element | jQuery
A template name or container.

---
#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/Scheduler/CustomTemplates/"
}

#####See Also#####
- [appointmentTooltipTemplate](/api-reference/10%20UI%20Widgets/dxScheduler/1%20Configuration/appointmentTooltipTemplate.md '/Documentation/ApiReference/UI_Components/dxScheduler/Configuration/#appointmentTooltipTemplate')
- [Customize Individual Views](/concepts/05%20Widgets/Scheduler/060%20Views/020%20Customize%20Individual%20Views.md '/Documentation/Guide/UI_Components/Scheduler/Views/Customize_Individual_Views/')
- [Customize Appointment Tooltip](/concepts/05%20Widgets/Scheduler/030%20Appointments/060%20Customize%20Appointment%20Tooltip.md '/Documentation/Guide/UI_Components/Scheduler/Appointments/Customize_Appointment_Tooltip/')
- [Custom Templates](/concepts/05%20Widgets/zz%20Common/30%20Templates/10%20Custom%20Templates.md '/Documentation/Guide/UI_Components/Common/Templates/#Custom_Templates')

<!-- import * from 'api-reference\10 UI Components\dxScheduler\1 Configuration\appointmentTemplate.md' -->