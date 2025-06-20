<!--TITLE: Loop Number Of Times Command -->
<!-- SUBTITLE: a command in the Loop group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Loop &gt; Loop Number Of Times


# Loop Number Of Times Command


## What does this command do?
This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to perform a series of commands a specified amount of times.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the How Many Times to perform the Loop](#param_0)
- [Optional - Please Specify the Define Start Value](#param_1)
- [Optional - Please Select the Variable Name to Store Current Loop Times (First Time Value is 'Start Value + 1')](#param_2)
- [Optional - Please Select the Variable Name to Store the Number of Loops (First Time Value is 0)](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the How Many Times to perform the Loop


<dl>
<dt>What to input</dt><dd>Enter the amount of times you would like to perform the encased commands.</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>5 or {vNum}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>5</strong> | Specify **5** for Loop Times |
| <strong>{vNum}</strong> | Specify Value of Variable **vNum** for Loop Times |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Define Start Value


<dl>
<dt>What to input</dt><dd>Enter the Starting Value of the loop.</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>5 or {vStart}</dd>
<dt>Remarks</dt><dd>If Start Value is <strong>0</strong> and Loop Times is <strong>5</strong>, it Loops <strong>5</strong> times.
If Start Value is <strong>1</strong> and Loop Times is <strong>5</strong>, it Loops <strong>4</strong> times.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>5</strong> | Specify **5** for Start Value |
| <strong>{vStart}</strong> | Specify Value of Variable **vStart** for Start Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Variable Name to Store Current Loop Times (First Time Value is 'Start Value + 1')


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
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
### Optional - Please Select the Variable Name to Store the Number of Loops (First Time Value is 0)


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: BeginNumberOfTimesLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/25 09:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
