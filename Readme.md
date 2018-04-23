# How to create a knob-like gauge 


<p>The following example illustrates a gauge control that looks and behaves like a typical 'knob' element of a real-life dashboard. This knob replicates the knob-like appearance and provides the capability to interactively modify its value via mouse clicks.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-create-a-knob-like-gauge-e3335/11.1.5+/media/b5aca44e-e490-11e6-80bf-00155d62480c.png"></p>


<h3>Description</h3>

<p>In this example, the knob-like gauge imitates the appearance of a real volume control. It is achieved by using custom templates for an arc scale&#39;s needle and layer elements. For your convenience, these templates are stored in the <strong>Kno</strong><strong>bRestoreDic</strong><strong>tionary</strong><strong>.</strong><strong>x</strong><strong>a</strong><strong>ml</strong> file with <strong>Oscilloscope</strong><strong>NeedleTemplate </strong>and <strong>OscilloscopeScaleLayerTemplate</strong> names, and thus can be easily re-used in your application.</p><p>The <strong>IsInteractive </strong>property of a gauge&#39;s needle<strong> </strong>is set to<strong> True</strong><strong> </strong>to enable its interactivity.</p><p>Finally, below the knob-like gauge, there is a <strong>Label</strong> control, which is bound to the <strong>Value </strong>property of a needle to display the current volume set by knob.</p>

<br/>


