<!--TITLE: Set DataTable Value Command -->
<!-- SUBTITLE: a command in the DataTable group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable &gt; DataTable Action &gt; Set DataTable Value


# Set DataTable Value Command


## What does this command do?
This command allows you to set the DataTable value


## When would I want to use this command?
Use this command when you want to set the DataTable value.


<a id="param_list"></a>
## Command Parameters
- [[5000,0x00001388] Please Select the DataTable Variable Name](#param_0)
- [[7000,0x00001B58] Optional - Please Select the Column type](#param_1)
- [[8000,0x00001F40] Please Specify the Name or Index of the Column](#param_2)
- [[9000,0x00002328] Please Specify the Value to Set](#param_3)
- [[9000,0x00002328] Optional - Please Specify the Index of the Row](#param_4)
- [[2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### [5000,0x00001388] Please Select the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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
### [7000,0x00001B58] Optional - Please Select the Column type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Column Name</strong> or  <strong>Index</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Column Name</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Column Name</strong> | Specify the Column Name like **Name** |
| <strong>Index</strong> | Specify the Column Index like **0** or **1** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### [8000,0x00001F40] Please Specify the Name or Index of the Column


<dl>
<dt>What to input</dt><dd>Enter or Select the Number or Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>id or 0 or -1 or {vColumn}</dd>
<dt>Remarks</dt><dd>If <strong>-1</strong> is specified for Column Index, it means the last column.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>id</strong> | Specify **id** for Column Name |
| <strong>0</strong> | Specify **0** for Column Index |
| <strong>-1</strong> | Specify Last Column Index |
| <strong>{vColumn}</strong> | Specify Value of Variable **vColumn** for Column Name or Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### [9000,0x00002328] Please Specify the Value to Set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** |
| <strong>123</strong> | Specify **123** |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### [9000,0x00002328] Optional - Please Specify the Index of the Row


<dl>
<dt>What to input</dt><dd>Enter or Select the Number</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or -1 or 1 or {vRowIndex}</dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Row</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify First Row Index |
| <strong>-1</strong> | Specify Last Row Index |
| <strong>1</strong> | Specify **1** for Row Index |
| <strong>{vRowIndex}</strong> | Specify Value of Variable **vRowIndex** for Row Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### [2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SetDataTableValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/25 08:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
