<!--TITLE: Format Number Command -->
<!-- SUBTITLE: a command in the Numerical group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Numerical &gt; Format Number


# Format Number Command


## What does this command do?
This command allows you to Format Number.


## When would I want to use this command?
Use this command when you want to Format Number.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Numerical Value](#param_0)
- [Please Specify the Number Format](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the Numerical Value


<dl>
<dt>What to input</dt><dd>Enter or Select the Numerical Value</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify **1** for Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Value |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Number Format


<dl>
<dt>What to input</dt><dd>Enter or Select the Number Format</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>0.# or C or {vFormat}</dd>
<dt>Remarks</dt><dd>For more detailed information, please refer to this URL.
https://learn.microsoft.com/en-us/dotnet/standard/base-types/custom-numeric-format-strings
https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-numeric-format-strings</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0.#</strong> | Specify **0.#** for Format |
| <strong>C</strong> | Specify **C** for Format |
| <strong>{vFormat}</strong> | Specify Value of Variable **vFormat** for Format |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
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
Automation Class Name: FormatNumberCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/25 09:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
