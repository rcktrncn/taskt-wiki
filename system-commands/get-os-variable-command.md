<!--TITLE: Get OS Variable Command -->
<!-- SUBTITLE: a command in the System group. -->
[Go To Automation Commands Overview](/automation-commands.md)


System &gt; Get OS Variable


# Get OS Variable Command


## What does this command do?
This command allows you to exclusively select a system/environment variable


## When would I want to use this command?
Use this command to exclusively retrieve a system variable


<a id="param_list"></a>
## Command Parameters
- [Please Select the System Variable](#param_0)
- [Please Select the Variable Name to Store Result](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the System Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>BootDevide or Name</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Variable Name to Store Result


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
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetOSVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/25 09:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
