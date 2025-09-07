<!--TITLE: Append Row Command -->
<!-- SUBTITLE: a command in the Excel group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel &gt; Row &gt; Append Row


# Append Row Command


## What does this command do?
Append to last row of sheet.


## When would I want to use this command?
Use this command will take in a comma seprerated value and append it to the end of an excel sheet.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Excel Instance Name](#param_0)
- [Please Specify the Value to Set](#param_1)
- [Optional - Please Specify the Text Separator](#param_2)
- [Optional - Please Select the Column Type](#param_3)
- [Optional - Please Specify the Column Location or Index](#param_4)
- [Optional - Please Select the Value Type](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


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
### Please Specify the Value to Set


<dl>
<dt>What to input</dt><dd>Enter or Select the Text or Number</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>Hello,World or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello,World</strong> | Specified **Hello** and **World**. |
| <strong>{vText}</strong> | Specify Value of Variable **vText** for Value To Set |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Text Separator


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>, or {vSep}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>,</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>,</strong> | Specify **,** for Text Separator |
| <strong>{vSep}</strong> | Specify Value of Variable **vSep** for Text Separator |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Column Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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
### Optional - Please Specify the Column Location or Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Column Location (Text) or Index (Number)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>A or 1 or {vColumn}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
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
### Optional - Please Select the Value Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Cell</strong> or  <strong>Formula</strong> or  <strong>Format</strong> or  <strong>Font Color</strong> or  <strong>Back Color</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Cell</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Cell</strong> | Specify the Cell Value |
| <strong>Formula</strong> | Specify the Cell Formula, like **=SUM(A1:A10)** |
| <strong>Format</strong> | Specify the Cell Format |
| <strong>Font Color</strong> | Specify the Cell Text Color |
| <strong>Back Color</strong> | Specify the Cell Background Color |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelAppendRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/07/25 06:35 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
