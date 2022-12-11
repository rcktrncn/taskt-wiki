<!--TITLE: Get JSON Value List Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Get/Set &gt; Get JSON Value List


# Get JSON Value List Command


## What does this command do?
This command allows you to parse a JSON object into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
- [Supply the JSON text or variable requiring extraction](#param_0)
- [Specify a JSON extractor (JSONPath)](#param_1)
- [Please select the variable to receive the extracted Result](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Supply the JSON text or variable requiring extraction


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Instance Type</dt><dd>JSON</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{&quot;id&quot;:2}</strong> or <strong>{vSomeVariable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Specify a JSON extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Input a JSON token extractor</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>$.id</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the variable to receive the extracted Result


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetJSONValueListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)