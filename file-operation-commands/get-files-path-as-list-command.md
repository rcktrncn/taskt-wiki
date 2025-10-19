<!--TITLE: Get Files Path As List Command -->
<!-- SUBTITLE: a command in the File Operation group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation &gt; Get Files Path As List


# Get Files Path As List Command


## What does this command do?
This command returns a list of file paths from a specified location


## When would I want to use this command?
Use this command to return a list of file paths from a specific location.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Folder Path](#param_0)
- [Optional - Please Specify the File Name Filter](#param_1)
- [Optional - Please Select the File Name Check Method](#param_2)
- [Optional - Please Select the Case Sensitive](#param_3)
- [Optional - Please Select the Trim Before Check](#param_4)
- [Optional - Please Specify the Extension](#param_5)
- [Please Select the List Variable Name to Store Result](#param_6)
- [Optional - Please Specify the Wait Time for the Folder to Exist (sec)](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Specify the Folder Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Folder Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>C:\temp or {vFilePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp</strong> | Specify **C:\temp** for Folder Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for Folder Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the File Name Filter


<dl>
<dt>What to input</dt><dd>Enter or Select the File Name Filter</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>hello or {vName}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Empty and Search All Files</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>hello</strong> | Specify **hello** for File Name Filter |
| <strong>{vName}</strong> | Specify Variable Name **vName** for File Name Filter |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the File Name Check Method


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Contains</strong> or  <strong>Starts with</strong> or  <strong>Ends with</strong> or  <strong>Exact match</strong> or  <strong>Not Contains</strong> or  <strong>Not Starts with</strong> or  <strong>Not Ends with</strong> or  <strong>Not Match</strong> or  <strong>Wildcard</strong> or  <strong>Not Wildcard</strong> or  <strong>Not Empty</strong> or  <strong>Is Number</strong> or  <strong>Is Boolean</strong> or  <strong>Is Boolean Loose</strong> or  <strong>Is Empty</strong> or  <strong>Is Not Number</strong> or  <strong>Is Not Boolean</strong> or  <strong>Is Not Boolean Loose</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Contains</strong> | It's like Comparing whether to Contains **hello**. |
| <strong>Starts with</strong> | It's like Comparing whether to Starts With **hello**. |
| <strong>Ends with</strong> | It's like Comparing whether to Ends With **hello**. |
| <strong>Exact match</strong> | It's like Comparing whether an Exact match to **hello**. |
| <strong>Not Contains</strong> | It's like Comparing whether to Not Contains **hello**. |
| <strong>Not Starts with</strong> | It's like Comparing whether to Not Starts With **hello**. |
| <strong>Not Ends with</strong> | It's like Comparing whether to Not Ends With **hello**. |
| <strong>Not Match</strong> | It's like Comparing whether an Not Matche to **hello**. |
| <strong>Not Empty</strong> | This determines not empty text. |
| <strong>Wildcard</strong> | Check for Wildcard match. |
| <strong>Not Wildcard</strong> | Check for Wildcard Not match. |
| <strong>Is Number</strong> | This determines whether a number. |
| <strong>Is Boolean</strong> | This determines whether a boolean, such as **True** or **False**. |
| <strong>Is Boolean Loose</strong> | This determines whether it is a loose boolean, such as **True**, **False**, **Yes**, **No**, **1**, or **0**. |
| <strong>Is Empty</strong> | This determines empty text. |
| <strong>Is Not Number</strong> | This determines whether it is **Not** a number. |
| <strong>Is Not Boolean</strong> | This determines whether it is **Not** a boolean, such as **True** or **False**. |
| <strong>Is Not Boolean Loose</strong> | This determines whether it is **Not** a loose boolean, such as **True**, **False**, **Yes**, **No**, **1**, or **0**. |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Case Sensitive


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Yes</strong> | Check Method is Case Sensitive |
| <strong>No</strong> | Check Method is NOT Case Sensitive |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Trim Before Check


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Trim</strong> or  <strong>Trim Start</strong> or  <strong>Trim End</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Trim</strong> | Remove White Space at the Start and End of Text |
| <strong>Trim Start</strong> | Remove White Space at the Start of Text |
| <strong>Trim End</strong> | Remove White Space at the End of Text |
| <strong>No</strong> | Not Trim |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Extension


<dl>
<dt>What to input</dt><dd>Enter or Select the Extention</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>txt or {vExtension}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Empty and Search All Files</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>txt</strong> | Specify text file for Extension |
| <strong>{vExtension}</strong> | Specify Value of Variable **vExtension** for Extension |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Select the List Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vList or {vList}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vList</strong> | Specify Variable Name **vList** |
| <strong>{vList}</strong> | Specify Variable Name **vList** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Wait Time for the Folder to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Folder is not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


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
Automation Class Name: GetFilesPathAsListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/19/25 05:27 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
