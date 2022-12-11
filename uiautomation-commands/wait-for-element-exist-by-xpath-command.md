<!--TITLE: Wait For Element Exist By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Search &gt; Wait For Element Exist By XPath


# Wait For Element Exist By XPath Command


## What does this command do?
This command allows you to Wait until the AutomationElement exists using by XPath.


## When would I want to use this command?



## Command Parameters
- [Please specify AutomationElement Variable](#param_0)
- [Please specify search XPath](#param_1)
- [Please specify how many seconds to wait for the AutomationElement to exist](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify AutomationElement Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>AutomationElement</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify search XPath


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>//Button[@Name=&quot;OK&quot;]</strong> or <strong>{vXPath}</strong></dd>
<dt>Remarks</dt><dd>XPath does not support to use parent, following-sibling, and preceding-sibling for root element.</dd>
</dl>




<a id="param_2"></a>
### Please specify how many seconds to wait for the AutomationElement to exist


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>10</strong> or <strong>{vWait}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
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
Automation Class Name: UIAutomationWaitForElementExistByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)