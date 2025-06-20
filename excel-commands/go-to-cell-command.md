<!--TITLE: Go To Cell Command -->
<!-- SUBTITLE: a command in the Excel group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel &gt; Cell &gt; Go To Cell


# Go To Cell Command


## What does this command do?
This command moves to a specific cell.


## When would I want to use this command?
Use this command when you want to move to a new cell from your currently selected cell.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Excel Instance Name](#param_0)
- [Please Specify the Cell Location](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the Excel Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel Instance Name</dd>
<dt>Value</dt><dd>Excel Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>RPAExcel or {vInstance}</dd>
<dt>Remarks</dt><dd>Please specify the Excel Instance Name created by <strong>Create Excel Instance</strong> command in advance.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPAExcel</strong> | Specify **RPAExcel** for Excel Instance Name |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for Excel Instance Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Cell Location


<dl>
<dt>What to input</dt><dd>Enter or Select the Cell Location like <strong>A1</strong></dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>A1 or B10 or {vAddress}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>A1</strong> | Specify **A1** |
| <strong>B10</strong> | Specify **B10** |
| <strong>{vAddress}</strong> | Specify Value of Variable **vAddress** for Cell Location |


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
Automation Class Name: ExcelGoToCellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/25 09:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
