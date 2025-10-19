<!--TITLE: Set One Window State Command -->
<!-- SUBTITLE: a command in the Window group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Window &gt; One Window Name Actions &gt; Set One Window State


# Set One Window State Command


## What does this command do?
This command Set State one Window.


## When would I want to use this command?
Use this command when you want to Set State one Window.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Window Name](#param_0)
- [Optional - Please Select the Check Method for the Window Name](#param_1)
- [Please Select the State of the Window](#param_2)
- [Optional - Please Selection Method for the Window Name](#param_3)
- [Optional - Please Specify the Window Index](#param_4)
- [Optional - Please Specify the Wait Time for the Window to Exist (sec)](#param_5)
- [Optional - Please Select the Variable Name to Store Window Name Result](#param_6)
- [Optional - Please Select the Variable Name to Store Window Handle Result](#param_7)
- [Optional - Please Select the Case Sensitive Checking for Window Names](#param_8)
- [Optional - Please Select the Trim before Check Window Names](#param_9)
- [Optional - Please Specify the Wait Time between Finding the Window and Executing Action (sec)](#param_10)
- [Optional - Please Select the Activate Window Before Action](#param_11)
- [Optional - Please Specify the Comment Field](#param_12)


<a id="param_0"></a>
### Please Select the Window Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Name</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Untitled - Notepad</strong> | Specify the **Notepad** |
| <strong>{Window.CurrentWindowName}</strong> | Specify the Current Activate Window |
| <strong>{vWindow}</strong> | Specify Value of Variable **vWindow** for Window Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the Check Method for the Window Name


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


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the State of the Window


<dl>
<dt>What to input</dt><dd>Enter or Select the Window State Text or Number</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Maximize</strong> or  <strong>Minimize</strong> or  <strong>Restore</strong> or  <strong>3</strong> or  <strong>2</strong> or  <strong>1</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Maximize</strong> | Specifiy Maximize |
| <strong>3</strong> | Specifiy Maximize |
| <strong>2</strong> | Specifiy Minimize |
| <strong>1</strong> | Specifiy Restore |
| <strong>{vState}</strong> | Specify Value of Variable **vState** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Selection Method for the Window Name


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>First</strong> or  <strong>Last</strong> or  <strong>Index</strong></dd>
<dt>Remarks</dt><dd>Specify when there are Multiple Matching Windows<br><br>
<strong>Optional</strong><br>Default Value is <strong>First</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>First</strong> | Specify the First Window |
| <strong>Last</strong> | Specify the Last Window |
| <strong>Index</strong> | the Window specifed by Index. **0** means First Window |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Window Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Index</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or 1 or {vIndex}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify the First Window |
| <strong>1</strong> | Specify **1** for Window Index |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Window Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Wait Time for the Window to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Window is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Variable Name to Store Window Name Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vWin or {vWin}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vWin</strong> | Specify Variable Name **vWin** |
| <strong>{vWin}</strong> | Specify Variable Name **vWin** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Variable Name to Store Window Handle Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>WindowHandle Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Select the Case Sensitive Checking for Window Names


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


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please Select the Trim before Check Window Names


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


[prev](#param_9) / [list](#param_list) / [next](#param_10)


</div>


<a id="param_10"></a>
### Optional - Please Specify the Wait Time between Finding the Window and Executing Action (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_10) / [list](#param_list) / [next](#param_11)


</div>


<a id="param_11"></a>
### Optional - Please Select the Activate Window Before Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_11) / [list](#param_list) / [next](#param_12)


</div>


<a id="param_12"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_12) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SetOneWindowStateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/19/25 05:27 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
