<!--TITLE: Move Window By Window Handle Command -->
<!-- SUBTITLE: a command in the Window group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Window &gt; Window Handle Actions &gt; Move Window By Window Handle


# Move Window By Window Handle Command


## What does this command do?
This command moves a window to a specified location on screen.


## When would I want to use this command?
Use this command when you want to move an existing window by name to a certain point on the screen.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Window Handle Variable Name](#param_0)
- [Please Specify the X horizontal coordinate (pixel) for the Window's Location](#param_1)
- [Please Specify the Y vertical coordinate (pixel) for the Window's Location](#param_2)
- [Optional - Please Specify the Wait Time for the Window to Exist (sec)](#param_3)
- [Optional - Please Select the When Window Is Minimized](#param_4)
- [Optional - Please Select the When Window Is Maximized](#param_5)
- [Optional - Please Specify the Wait Time between Finding the Window and Executing Action (sec)](#param_6)
- [Optional - Please Select the Variable Name to Store Window Name](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Select the Window Handle Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>WindowHandle Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the X horizontal coordinate (pixel) for the Window's Location


<dl>
<dt>What to input</dt><dd>Enter or Select the X Window Location</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>0 or 100 or {vXPos} or {Window.CurrentPosition}</dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify X Top Position |
| <strong>100</strong> | Specify **100** for X Position |
| <strong>{vXPos}</strong> | Specify Value of Variable **vXPos** for X Position |
| <strong>{Window.CurrentPosition}</strong> | Specify Current Position for X Position |
| <strong>{Window.CurrentXPosition}</strong> | Specify Current X Position for X Position |
| <strong>{Window.CurrentYPosition}</strong> | Specify Current Y Position for X Position |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Y vertical coordinate (pixel) for the Window's Location


<dl>
<dt>What to input</dt><dd>Enter or Select the Y Window Location</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>0 or 100 or {vYPos} or {Window.CurrentPosition}</dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify Y Left Position |
| <strong>100</strong> | Specify **100** for Y Position |
| <strong>{vYPos}</strong> | Specify Value of Variable **vYPos** for Y Position |
| <strong>{Window.CurrentPosition}</strong> | Specify Current Position for Y Position |
| <strong>{Window.CurrentXPosition}</strong> | Specify Current X Position for Y Position |
| <strong>{Window.CurrentYPosition}</strong> | Specify Current Y Position for Y Position |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Wait Time for the Window to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Window is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the When Window Is Minimized


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Execute</strong> or  <strong>Restore</strong> or  <strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Restore</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing To Do |
| <strong>Error</strong> | Rise an Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the When Window Is Maximized


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Execute</strong> or  <strong>Restore</strong> or  <strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Restore</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing To Do |
| <strong>Error</strong> | Rise an Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Wait Time between Finding the Window and Executing Action (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Variable Name to Store Window Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: MoveWindowByWindowHandleCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/07/25 06:35 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
