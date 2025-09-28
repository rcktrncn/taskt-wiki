<!--TITLE: Check Worksheet Exists Command -->
<!-- SUBTITLE: a command in the Excel group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel &gt; Worksheet &gt; Check Worksheet Exists


# Check Worksheet Exists Command


## What does this command do?
This command allows you to check existance sheet


## When would I want to use this command?
Use this command when you want to switch to a specific worksheet


<a id="param_list"></a>
## Command Parameters
- [[5000,0x00001388] Please Select the Excel Instance Name](#param_0)
- [[6000,0x00001770] Please Specify the Worksheet Name](#param_1)
- [[7000,0x00001B58] Please Select the Variable Name to Store Result](#param_2)
- [[2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### [5000,0x00001388] Please Select the Excel Instance Name


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
### [6000,0x00001770] Please Specify the Worksheet Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Worksheet Name</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>mySheet or {vSheet} or {Excel.CurrentWorksheet}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>mySheet</strong> | Specify **mySheet** for Worksheet Name |
| <strong>{vSheet}</strong> | Specify Value of Variable **vSheet** for Worksheet Name |
| <strong>{Excel.CurrentWorksheet}</strong> | Specify Current Worksheet Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### [7000,0x00001B58] Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Boolean Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>When the Sheet Exists, Result is <strong>True</strong></dd>
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
### [2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelCheckWorksheetExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/25 08:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
