<!--TITLE: Create DataTable From Excel File Command -->
<!-- SUBTITLE: a command in the Excel group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel &gt; File/Book &gt; Create DataTable From Excel File


# Create DataTable From Excel File Command


## What does this command do?
This command Open a File and Get Cell Values as a DataTable


## When would I want to use this command?
Use this command when you want to Open a File and Get Cell Values as a DataTable


<a id="param_list"></a>
## Command Parameters
- [Please Select the DataTable Variable Name](#param_0)
- [Please Specify the Workbook (Excel File) Path](#param_1)
- [Please Specify the Worksheet Name](#param_2)
- [Optional - Please Select the Column Type](#param_3)
- [Please Specify the Column Location or Index](#param_4)
- [Optional - Please Specify the Row Location](#param_5)
- [Optional - Please Select the Use the First Row as the Column Names (Value Type is Cell only)](#param_6)
- [Optional - Please Specify the Comment Field](#param_7)


<a id="param_0"></a>
### Please Select the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
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
### Please Specify the Workbook (Excel File) Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel File Path</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance Required</li><li>Support Extensions: xlsx,xlsm,xls,xlm,csv,ods</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd>C:\temp\myfile.xlsx or {vFilePath}</dd>
<dt>Remarks</dt><dd>If file does not contain extension, supplement extensions supported by Excel.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myfile.xlsx</strong> | Specify **C:\temp\myfile.xlsx** for File Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for File Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Worksheet Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Worksheet Name</dd>
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


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Column Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Range</strong> or  <strong>RC</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Range</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Range</strong> | Use Range, like **A**. It means first column. |
| <strong>RC</strong> | Use Row-Column, like **1**. It means first column. |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the Column Location or Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Column Location or Index</dd>
<dt>Sample Usage</dt><dd>A or 1 or {vColumn}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>A</strong> | Specify the First Column when **Range** is specified for Column Type. |
| <strong>1</strong> | Specify the First Column when **RC** is specified for Column Type. |
| <strong>{vColumn}</strong> | Specify Value of Variable **vColumn** for Column |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Row Location


<dl>
<dt>What to input</dt><dd>Enter or Select the Row Location</dd>
<dt>Sample Usage</dt><dd>1 or 2 or {vRow}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify the First Row |
| <strong>2</strong> | Specify **2** for Row Location |
| <strong>{vRow}</strong> | Specify Value of Variable **vRow** for Row Location |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Use the First Row as the Column Names (Value Type is Cell only)


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelCreateDataTableFromExcelFile
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/16/25 10:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
