<!--TITLE: Check Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Text Command


## What does this command do?
This command allows you to check a Text


## When would I want to use this command?
Use this command when you want to check a Text


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Supply the Text or Variable to Checked|Select or provide a variable or text value|**Hello** or **{vText}**||
|Please Select the Check Method||**Contains** or **Starts with** or **Ends with** or **Index of** or **Last Index of**||
|Please Specify Text to Check or Search||**Ha** or **{vSearchedText}**||
|Optional - Please Select Case sensitive (Default is Yes)|Indicate if only so many characters should be kept|**Yes** or **No**||
|Please select the variable to receive the result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










### Addtional Info about &quot;Please select the variable to receive the result&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Contains|Result is TRUE or FALSE|||
|Start with|Result is TRUE or FALSE|||
|End with|Result is TRUE or FALSE|||
|Index of|Result is a found position. If not found, the result is -1.|||
|Last Index of|Result is the last position found. If not found, the result is -1.|||




## Developer/Additional Reference
Automation Class Name: CheckTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/07/22 12:05 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)