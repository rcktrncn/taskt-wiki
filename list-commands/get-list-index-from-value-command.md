<!--TITLE: Get List Index From Value Command -->
<!-- SUBTITLE: a command in the List group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List &gt; List Index &gt; Get List Index From Value


# Get List Index From Value Command


## What does this command do?
This command allows you want to get list index from value


## When would I want to use this command?
Use this command when you want to get list index from value


<a id="param_list"></a>
## Command Parameters
- [[5000,0x00001388] Please Select the List Variable Name](#param_0)
- [[7000,0x00001B58] Optional - Please Specify the Value to Search](#param_1)
- [[8000,0x00001F40] Optional - Please Select the Search Method](#param_2)
- [[10000,0x00002710] Please Specify the v_Result](#param_3)
- [[2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### [5000,0x00001388] Please Select the List Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### [7000,0x00001B58] Optional - Please Specify the Value to Search


<dl>
<dt>What to input</dt><dd>Enter or Select the Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or Hello or {vValue}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Empty</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Value to Search |
| <strong>Hello</strong> | Specify **Hello** for Value to Search |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Value to Search |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### [8000,0x00001F40] Optional - Please Select the Search Method


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>First Index</strong> or  <strong>Last Index</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>First Index</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### [10000,0x00002710] Please Specify the v_Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>When List does not have value, Result is <strong>-1</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### [2147483647,0x7FFFFFFF] Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetListIndexFromValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/25 08:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
