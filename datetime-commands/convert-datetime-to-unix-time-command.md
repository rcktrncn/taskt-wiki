<!--TITLE: Convert DateTime To Unix Time Command -->
<!-- SUBTITLE: a command in the DateTime group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime &gt; Convert &gt; Convert DateTime To Unix Time


# Convert DateTime To Unix Time Command


## What does this command do?
This command allows you to Convert DateTime To Unix Time.


## When would I want to use this command?
Use this command when you want Convert DateTime To Unix Time.


<a id="param_list"></a>
## Command Parameters
- [[5000,0x00001388] Please Select the DateTime Variable Name](#param_0)
- [[7000,0x00001B58] Please Select the Variable Name to Store Unix Time](#param_1)
- [[2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### [5000,0x00001388] Please Select the DateTime Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DateTime Variable</dd>
<dt>Value</dt><dd>DateTime Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>{vDateTime}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>{vDateTime}</strong> | Specify Value of Variable **vDateTime** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### [7000,0x00001B58] Please Select the Variable Name to Store Unix Time


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
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


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### [2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ConvertDateTimeToUnixTimelCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/25 08:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
