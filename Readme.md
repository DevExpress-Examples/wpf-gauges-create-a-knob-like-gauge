<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128570577/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3335)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WPF Gauges - Create a Knob-like Gauge

This example customizes the [CircularGaugeControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Gauges.CircularGaugeControl). As a result, the control looks and behaves like a 'knob' element of a real-life dashboard.

![Knob-like Gauge](./media/b5aca44e-e490-11e6-80bf-00155d62480c.png)

## Implementation Details

Use custom templates for an arc scale's [needle](https://docs.devexpress.com/WPF/9957/controls-and-libraries/gauge-controls/visual-elements/circular-gauge/needle) (**OscilloscopeNeedleTemplate**) and [layer](https://docs.devexpress.com/WPF/9962/controls-and-libraries/gauge-controls/visual-elements/circular-gauge/layers) (**OscilloscopeScaleLayerTemplate**) elements to achieve the illustrated appearance. The **KnobResourceDictionary.xaml** file contains these templates.

Set the needle's [IsInteractive](https://docs.devexpress.com/WPF/DevExpress.Xpf.Gauges.ValueIndicatorBase.IsInteractive) property to `true` to allow users to change the gauge's value. The gauge stores its value in the needle's `Value` property.

## Files to Review

* [KnobResourceDictionary.xaml](./CS/DXGauges_Knobs/KnobResourceDictionary.xaml) (VB: [KnobResourceDictionary.xaml](./VB/DXGauges_Knobs/KnobResourceDictionary.xaml))
* [MainWindow.xaml](./CS/DXGauges_Knobs/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXGauges_Knobs/MainWindow.xaml))

## Documentation

* [CircularGaugeControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Gauges.CircularGaugeControl)
* [Circular Gauge Elements](https://docs.devexpress.com/WPF/9954/controls-and-libraries/gauge-controls/visual-elements/circular-gauge)
