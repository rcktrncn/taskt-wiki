<!--TITLE: Search And Delete DataTable Rows Command -->
<!-- SUBTITLE: a command in the DataTable group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable &gt; Row Action &gt; Search And Delete DataTable Rows


# Search And Delete DataTable Rows Command


## What does this command do?
This command allows you Delete specified DataTable Rows.


## When would I want to use this command?
Use this command when you want to Delete a specific Row.


<a id="param_list"></a>
## Command Parameters
- [[5000,0x00001388] Please Select the DataTable Variable Name](#param_0)
- [[6000,0x00001770] Please indicate tuples to delete column rows](#param_1)
- [[7000,0x00001B58] Please select overwrite option](#param_2)
- [[2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### [5000,0x00001388] Please Select the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vDataTable or {vDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDataTable</strong> | Specify Variable Name **vDataTable** |
| <strong>{vDataTable}</strong> | Specify Variable Name **vDataTable** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### [6000,0x00001770] Please indicate tuples to delete column rows


<dl>
<dt>What to input</dt><dd>Enter a tuple containing the column name and item you would like to remove.</dd>
<dt>Sample Usage</dt><dd>{ColumnName1,Item1},{ColumnName2,Item2}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### [7000,0x00001B58] Please select overwrite option


<dl>
<dt>What to input</dt><dd>Indicate whether this command should remove rows with all the constraints or remove them with 1 or more constraints</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>And</strong> or  <strong>Or</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




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
Automation Class Name: SearchAndDeleteDataTableRowsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/25 08:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
