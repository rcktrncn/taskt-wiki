<!--TITLE: Get Pixel Colour Command -->
<!-- SUBTITLE: a command in the Image group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image &gt; Get Pixel Colour


# Get Pixel Colour Command


## What does this command do?
This command gets a pixel at x,y coordinates from current screen.


## When would I want to use this command?
Use this command when you need to check a single pixel colour on the screen.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Specify the X Coordinate](#param_0)
- [Optional - Please Specify the Y Coordinate](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Optional - Please Specify the X Coordinate


<dl>
<dt>What to input</dt><dd>Enter or Select the X</dd>
<dt>Sample Usage</dt><dd>0 or 100 or {vXOffset}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for X |
| <strong>100</strong> | Specify **100** for X |
| <strong>{vXOffset}</strong> | Specify Value of Variable **vXOffset** for X |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Y Coordinate


<dl>
<dt>What to input</dt><dd>Y</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Y |
| <strong>100</strong> | Specify **100** for Y |
| <strong>{vYOffset}</strong> | Specify Value of Variable **vYOffset** for Y |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetPixelColourCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/30/25 12:02 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
