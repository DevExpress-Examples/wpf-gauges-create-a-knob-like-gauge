<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128570577/11.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3335)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [KnobResourceDictionary.xaml](./CS/DXGauges_Knobs/KnobResourceDictionary.xaml) (VB: [KnobResourceDictionary.xaml](./VB/DXGauges_Knobs/KnobResourceDictionary.xaml))
* [MainWindow.xaml](./CS/DXGauges_Knobs/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXGauges_Knobs/MainWindow.xaml))
<!-- default file list end -->
# How to create a knob-like gauge 


<p>The following example illustrates a gauge control that looks and behaves like a typical 'knob' element of a real-life dashboard. This knob replicates the knob-like appearance and provides the capability to interactively modify its value via mouse clicks.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-create-a-knob-like-gauge-e3335/11.1.5+/media/b5aca44e-e490-11e6-80bf-00155d62480c.png"></p>


<h3>Description</h3>

<p>In this example, the knob-like gauge imitates the appearance of a real volume control. It is achieved by using custom templates for an arc scale&#39;s needle and layer elements. For your convenience, these templates are stored in the <strong>Kno</strong><strong>bRestoreDic</strong><strong>tionary</strong><strong>.</strong><strong>x</strong><strong>a</strong><strong>ml</strong> file with <strong>Oscilloscope</strong><strong>NeedleTemplate </strong>and <strong>OscilloscopeScaleLayerTemplate</strong> names, and thus can be easily re-used in your application.</p><p>The <strong>IsInteractive </strong>property of a gauge&#39;s needle<strong> </strong>is set to<strong> True</strong><strong> </strong>to enable its interactivity.</p><p>Finally, below the knob-like gauge, there is a <strong>Label</strong> control, which is bound to the <strong>Value </strong>property of a needle to display the current volume set by knob.</p>

<br/>


<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-gauges-create-a-knob-like-gauge&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-gauges-create-a-knob-like-gauge&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
