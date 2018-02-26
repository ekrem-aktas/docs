---
title: "Action Reference"
parent: "rg-version-2"
---

## 1 Introduction

The tables below list all the standard actions for Mendix. There is one table per category. For more detailed information, see the following ATS Reference Guide pages: 

* [Mendix Actions](/ats/refguide/rg-version-1/mendix-actions)
* [Dialog](/ats/refguide/rg-version-1/dialog)
* [Mendix App Store Widget Actions](/ats/refguide/rg-version-1/mendix-appstore-widgets-actions)
* [ATS Core Actions](/ats/refguide/rg-version-1/ats-core-actions)
* [Selenium Actions](/ats/refguide/rg-version-1/selenium-actions)

## 2 Widget – Set

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Set BooleanSlider Value          | BooleanSlider                    | Checks if the given value is available for the BooleanSlider and sets the value. |
| Set BootstrapRTE Value           | BootstrapRTE                     | Sets the given value as current value for the BootstrapRTE value. Strings can be formatted via html-code |
| Set Checkbox Set Selector Value  | Checkbox Set Selector            | Checks/clears the **Select all** check box. |
| Set Checkbox Set Selector Value (all) | Checkbox Set Selector       | Checks/clears the **Select all** check box. |
| Set Checkbox Value               | Checkbox                         | Sets the value of a check box. |
| Set CKEditor Value               | CKEditor                         | Sets the CKEditor content value. |
| Set File Manager                 | FileManager                      | Sets the file manager to the given file path to upload a file. |
| Set Grid Selector Checkbox Value | Grid Selector                    | Checks/clears the check box. |
| Set Grid Selector Radiobutton checked  | Grid Selector              | Selects the radio button for the given column and row caption. |
| Set InputReferenceSelector Value | InputReferenceSelector           | Sets the input reference selector to the given value. |
| Set ListView Search              | ListView                         | Sets the list view search text. |
| Set Row Cell Value               | DataGrid                         | Set the cell value in a data grid row. |
| Set Simple Checkbox Set Selector Value | Simple Checkbox Set Selector | Checks/clears the check box found by a given entity attribute value. |
| Set Value | TextBox, TextArea, DatePicker, DropDown, RadioButton, ReferenceSelector, SearchInput Text, SearchInput DropDown, OnChange Inputbox | Sets the text value of a text box, text area, date input, reference selector, or enum selector. |
| Set Value (by index) | DropDown, ReferenceSelector, SearchInput DropDown | Sets the value of a drop-down menu by index (for example, EnumSelect or ReferenceSelector). |

## 3 Widget – Get

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Get Active Tab Caption  | TabContainer                       | Returns the caption of the active tab page. |
| Get BooleanSlider Value | BooleanSlider                       | Returns the current value of the BooleanSlider as a string. |
| Get BootstrapRTE Value  | BootstrapRTE | Returns the current BootstrapRTE value as an HTML string. |
| Get Checkbox Set Selector Value | Checkbox Set Selector | Finds the check box by column caption and cell value and returns its value. |
| Get Checkbox Set Selector Value (all) | Checkbox Set Selector | Returns the **Select all** check box value. |
| Get Checkbox Value | Checkbox | Returns true if the check box is checked. |
| Get CKEditor Value | CKEditor | Returns the CKEditor value. |
| Get Grid Selector Box Value | Grid Selector Box | Returns the current check box/radio button value. |
| Get Index | DropDown, ReferenceSelector, SearchInput DropDown | Gets the index of selected values in a drop-down menu (for example, an EnumSelect or ReferenceSelector). |
| Get InputReferenceSelector Value | InputReferenceSelector | Returns the current value of the InputReferenceSelector. |
| Get Item/Row Index | DataGrid, TemplateGrid, ListView | Gets the index of a row in a data grid or an item in a template grid or list view. |
| Get Row Cell Value | DataGrid | Gets the cell value of a data grid row. |
| Get Simple Checkbox Set Selector Value | Simple Checkbox Set Selector | Returns the current value of the check box found by the entity attribute value. |
| Get Total Item/Row Count | DataGrid, TemplateGrid, ListView | Gets the total grid count from the paging status. |
| Get Validation Message | All widgets | Returns the validation message of a widget. |
| Get Value | TextBox, TextArea, DatePicker, DropDown, RadioButton, ReferenceSelector, SearchInput Text, SearchInput DropDown, Label, OnChange Inputbox. |
| Get Visible Item/Row Count | DataGrid, TemplateGrid, ListView | Returns the number of currently visible items/rows in a template grid, data grid, or list view. |
| Groupbox is Collapsed | GroupBox | Gets the group box collapsed state: true if collapsed, otherwise false. |

## 4 Widget – Assert

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Assert Active Tab Caption | TabContainer | Asserts a certain value for the caption of an active tab page. |
| Assert BooleanSlider Value | BooleanSlider | Asserts that the BooleanSlider is set to the given value. |
| Assert BootstrapRTE Value | BootstrapRTE | Asserts that the BootstrapRTE value is equal to the given value. |
| Assert Checkbox Set Selector Value | Checkbox Set Selector | Finds the check-box-by-entity attribute and asserts that the check box is set to the given value. |
| Assert Checkbox Value | CheckBox | Asserts the value of a check box. |
| Assert CKEditor Value | CKEditor | Compares the CKEditor value with the given value. |
| Assert Grid Selector Value | Grid Selector | Asserts the value of check box/radio button. |
| Assert InputReferenceSelector Value | InputReferenceSelector | Asserts that the input reference selector has the given value. |
| Assert Simple Checkbox Set Selector Value | Simple Checkbox Set Selector | Asserts that the check box found by the given entity attribute value is checked/cleared. |
| Assert Validation Message | All widgets | Asserts a validation message with a certain text. |
| Assert Value | TextBox, TextArea, DatePicker, DropDown, RadioButton, ReferenceSelector, SearchInput Text, SearchInput DropDown, Label, OnChange Inputbox | Asserts the text value from a text box, text area, date input, radio button, or drop-down menu. |
| Dropdown has Option | DropDown, ReferenceSelector, SearchInput DropDown | Returns true if the value is available in a drop-down menu. |

## 5 Widget – Find

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Find/Assert DataGrid Row | DataGrid | Finds/asserts a data grid row by a certain column value(s). |
| Find/Assert Menu Item | NavigationTree, MenuBar, SimpleMenuBar | Finds/asserts a visible menu item in a navigation tree, menu bar, and simple menu bar. |
| Find/Assert Widget | All widgets | Finds/asserts a Mendix widget by its given name. It is possible to use a sequence of names as a path (separated by spaces). |
| Find Checkbox Set Selector | Checkbox Set Selector | Finds a check box by a given cell value and column caption. Returns the first match. |
| Find Checkbox Set Selector (all) | Checkbox Set Selector | Returns the **Select all** check box. |
| Find Grid Selector | Grid Selector | Finds a check box/radio button by the column and row caption. |
| Find Item/Row | DataGrid, TemplateGrid, ListView | Finds a row/item in a data grid, template grid, or list view by index. |
| Find Item/Row (by child element) | DataGrid, TemplateGrid, ListView | Finds an item or row of a template grid, data grid, or list view containing a specified element. |
| Find Selected Item/Row | DataGrid, TemplateGrid, ListView | Returns the first selected item/row object. |
| Find Simple Checkbox Set Selector | Simple Checkbox Set Selector | Finds the check box by the given value. |
| Find Widget Child Node | All widgets | Find a node within a Mendix widget. Also matches the widget node itself. The action is limited to search only within widgets that are visible. |

## 6 Widget – Other

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Click DataGrid Row | DataGrid | Clicks a data grid row by column value. |
| Click Dropdown Div Converter dropdown button | Dropdown Div Converter | Clicks the drop-down `div` converter drop-down button. |
| Click Dropdown Div Converter split button | Dropdown Div Converter | Clicks the drop-down `div` converter split button. |
| Click Menu Item | NavigationTree, MenuBar, SimpleMenuBar | Clicks a menu item in a navigation tree, menu bar, and simple menu bar. |
| Click Widget | All widgets | Clicks a Mendix widget (for example, button, link, image) by its name. |
| Click Widget Button | ListView, ReferenceSelector | Refresh Button / Loadmore / ClearSearchField (ListView) Goto, / Adds (ReferenceSelector). |
| Close GroupBox | GroupBox | Closes a group box. |
| Open GroupBox | GroupBox | Opens a group box. |
| Sort DataGrid | DataGrid | Sorts a data grid by the given column. |
| Toggle BooleanSlider Value | BooleanSlider | Toggles the value of the Booleanslider. |
| Toggle Checkbox Set Selector | Checkbox Set Selector | Finds a check-box by a given entity attribute and inverses the value. |
| Toggle Checkbox Set Selector (all) | Checkbox Set Selector | Inverses the **Select all** check box. |
| Toggle Checkbox Value | Checkbox | Clicks a check box to toggle its value. |
| Toggle Grid Selector Checkbox Value | Grid Selector | Inverses the check box found by a given column and row caption. |
| Toggle Simple Checkbox Set Selector Value | Simple Checkbox Set Selector | Inverses the value of the check box found by the given entity attribute value. |

## 7 Mendix

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Assert Current Page | N/A | Asserts that a certain page is open by checking the current page title. Note that the page title may depend on the user's language! For dialog boxes, use the Find/Assert Dialog action. |
| Cancel Dialog | ConfirmationDialog | Clicks Cancel on a confirmation dialog box. |
| Click/Doubleclick | All web elements | Performs a click or double-click and a wait for Mendix activities. |
| Close Dialog | Window, DialogMessage, ConfirmationDialog | Clicks the X button on a confirmation, error, warning, or info dialog box. |
| Confirm Dialog | ConfirmationDialog, DialogMessage | Clicks Proceed/OK button on a confirmation, error, warning, or info dialog box. |
| Find/Assert Dialog | Window, DialogMessage, ConfirmationDialog | Finds/asserts a dialog box by title or type. |
| Get Current Page Title | N/A | Returns the current page/form title. |
| Get Dialog Message Text | ConfirmationDialog, DialogMessage | Gets the text from the message and confirmation dialog boxes. |
| Login | Standard login page | Logs in to the Mendix application with the standard login page or on the cloud using MxID. |
| Logout | N/A | Triggers the logout/logoff from application via the Client API. Use this keyword in the teardown of your test cases to end the user session. This will work regardless of the UI state. |
| Mendix wait | N/A | Injects Mendix scripts and waits. |
| Open Mendix Application | N/A | Opens a Mendix application at the website URL in a browser with Mendix-specific settings. |

## 8 Web

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Accept Browser Alert | N/A | Accepts the alert available. |
| Clear WebElement | WebElement | Clears a web element (input or text area). |
| Close Window | N/A | Closes the currently active window. Does not switch to another window automatically. |
| Close Window & Auto-Switch | N/A | Closes the currently active window and automatically switches to the next one. |
| Dismiss Browser Alert | N/A | Dismisses the alert available. |
| Element matches Selector | WebElement | Returns whether the given element matches the selector. |
| Execute Javascript Integer | N/A | Executes the JavaScript snippet. Runs asynchronously when the timeout is set. Returns an integer. |
| Execute Javascript String | N/A | Executes the JavaScript snippet. Runs asynchronously when the timeout is set. Returns a string. |
| Execute Javascript WebElement | N/A | Executes the JavaScript snippet. Runs asynchronously when the timeout is set. Returns a web element. |
| Find Element | N/A | Finds a web element. It optionally restricts the search to the specified SearchContext element. The occurrence lets you specify which element to fetch from the result list, starting at 1 for the first element (defaults to the first element). |
| Find Element by CSS | N/A | Finds a web element by CSS. It optionally restricts search to the specified SearchContext element. The occurrence lets you specify which element to fetch from the result list, starting at 1 for the first element (defaults to the first element). |
| Find Element by ID | N/A | Finds a web element by the ID. It optionally restricts the search to the specified SearchContext element. The occurrence lets you specify which element to fetch from the result-list, starting at 1 for the first element (defaults to the first element). |
| Find Element by Sizzle | N/A | Finds a web element by Sizzle. Optionally restrict search to the specified SearchContext element. The occurrence lets you specify which element to fetch from the result list, starting at 1 for the first element (defaults to the first element). |
| Get Current Window Handle | N/A | Returns the handle (meaning, the identifier) of the currently active window. |
| Get Property Value | WebElement | Returns the property value from the web element. (Does not have access to Dojo widget properties). |
| Get Selected Option Index   | |
| Get Selected Option Text | | |
| Get Selected Option Value | | |
| Get Text | WebElement | |
| Is Element Displayed | WebElement | Returns true if the supplied element is displayed (visible). |
| Is Selected | WebElement | Checks whether the check box is selected. |
| Maximize | N/A | Maximizes the current browser window. |
| Open Application | N/A | Opens an application at the application's URL in a browser. |
| Open Website | N/A | |
| Select Option | | |
| Select Option by Index | | |
| Select Option by Text | | |
| Select Option by Value | | |
| Set Browser Dimensions | N/A | |
| Set Page Load Timeout | N/A | |
| Set Size | N/A | Sets the size of a browser window. |
| Switch to Default Frame | N/A | |
| Switch to Frame | N/A | |
| Switch to Next Window | N/A | Switches to the next open window. An error is thrown if there is only one window. Returns the window handle (meaning, the identifier) of the new active window. |
| Switch to Window | N/A | Switches to the window via its identifier. An error is thrown if the window is not found. |
| Unfocus WebElement | WebElement | |
| Wait for Condition | N/A | |
| Set Browser Dimensions | N/A | |
| Wait for Condition JS | N/A | Waits until the given expression returns true. |

## 9 Mouse & Keyboard

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Click | WebElement | Clicks in the middle of the given element. |
| Click Coordinates | N/A | Clicks a given point on the page as described by the X and Y offset. If no reference element is given, the upper-left corner of the page is used as point of origin for calculating the desired point. Otherwise, the upper-left corner of the reference element is used. |
| Doubleclick | WebElement | Performs a click or double-click and then a wait for Mendix activities. |
| Focus and Clear Element Value | WebElement | Sets an input element to an empty string. |
| Focus WebElement | WebElement | Focuses the web element and performs a wait afterwards. |
| Focus WebElement | WebElement | |
| Hover | WebElement | Hovers a web element. |
| Scroll to Element | WebElement | |
| Scroll to top | N/A                  | |
| Send Enter | N/A                  | Simulates pressing <kbd>Enter</kbd> in the element. |
| Send Keys | N/A                  | Simulates typing <kbd>Text</kbd>  into the element. |

## 10 Logic

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Assert | N/A | A hamcrest assert. |
| Assert 1 | N/A | Asserts that the value is 1. `([null]=0)` |
| Assert all not null | N/A | Fails if one of the objects is null. |
| Assert at least one not null | N/A | Fails if all the objects are null. |
| Assert Both not null | N/A | Fails if one or both objects are null. |
| Assert Condition Fails | N/A | This assert always fails. If an attached condition fails, it is simply not executed (and thus this keyword does not fail). (Use this keyword to assert that another keyword fails). |
| Assert containsNoString | N/A | Asserts false that the subject contains a string that is equal to matcher parameter (for example, `testcasetool` contains `case`, it fails `case`). |
| Assert containsString | N/A | Asserts that the subject contains a string that is equal to the matcher parameter (for example, `testcasetool` contains `case`). |
| Assert Element Attribute Equals | WebElement | Asserts that an attribute of the given element equals the specified value. |
| Assert Element matches Selector | WebElement | For Mendix 4-5, this returns whether the given element matches the selector. |
| Assert endsWith | N/A | Asserts that the subject ends with a string that is equal to the matcher parameter (for example, `testcase` ends with `case`). |
| Assert Equals | N/A | Asserts that the two values are equal. |
| Assert equalTo | N/A | Asserts that the subject is equal to matcher parameter (for example, `100` is equal to `100` or `house` is equal to `house`). |
| Assert equalToIgnoringCase | N/A | Asserts that the subject is equal to the matcher parameter while ignoring the case (for example, `house` is equal to `House`). |
| Assert equalToIgnoringWhiteSpace | N/A | Asserts that the subject is equal to the matcher parameter while ignoring whitespaces (for example, `testcase` is equal to `' testcase '`). |
| Assert false | N/A | Asserts the Bolean value to be false. |
| Assert greaterThan | N/A | Asserts that the subject is greater than the matcher parameter (for example, `1000` is greater than `100`). |
| Assert greaterThanOrEqualTo | N/A | Asserts that the subject is either greater than or equal to the matcher parameter (for example, `1000` is greater than `100`, `1000` is equal to `1000`). 
| Assert lessThan | N/A | Asserts that the subject is less than the matcher parameter (for example, `100` is less than `1000`). |
| Assert lessThanOrEqualTo | N/A | Asserts that the sbject is either less than or equal to the matcher parameter (for example, `100` is less than `1000`, `1000` is equal to `1000`). |
| Assert not equals | N/A | Asserts that two values are not equal. |
| Assert not false | N/A | |
| Assert not true | N/A | Either false or null. |
| Assert null | N/A | Fails if the object is not null. |
| Assert null (internal) | N/A | Allows a Boolean parameter to invert the result. |
| Assert Property Value | N/A | Gets the property/attribute from the web element and asserts that it equals the given value. |
| Assert startsWith | N/A | Asserts that the subject starts with a string that is equal to the matcher parameter (for example, `testcase` starts with `test`). |
| Assert true | N/A | |
| Assert XML equivalent | N/A | Asserts that two XMLs are equivalent. |
| Concatenate String | String | Concatenate strings. |
| If Null Then 0 (Integer) | N/A  | Checks the input value and sets it to 0 if it is null. |
| Is not Null | N/A | Returns true if object is not null, false otherwise. |
| Push ATS Scripts | N/A | Pushes generic ATS scripts to the client (jQuery, helpers functions). |
| RegExp Match | String | Return the n'th match of the given regular expression in the search string (uses JS `string.match`). |
| Return First Valid Boolean | Boolean | Returns the first Boolean from the parameter list that is not null. |
| Return First Valid Integer | Integer | Returns the first integer from the parameter list that is not null. |
| Return First Valid String | String | Returns the first string from the parameter list that is not null. |
| Return First Valid WebElement | WebElement | Returns the first web element from the parameter list that is not null. |
| Set Implicit Wait | N/A | |
| Set Return Value | N/A | |
| Sleep | N/A | The waits "sleep time" in milliseconds. |

## 11 Generators

| Action           | Supported Widgets | Description                              |
| ---------------- | ----------------- | ---------------------------------------- |
| Generate GUID | N/A | Generates and returns a GUI. |
| Get Current DateTime String | N/A | Returns the current date and time in the supplied format (Java date format) (for example, `yyyy-MM-dd HH:mm:ss`. |
| Random Number | N/A | Creates a random integer using `Math.floor(Math.random() * (max - min)) + min`. You need to define the min (included) and max (excluded). |
| Random String | N/A | Creates a random alphanumeric string using `Math.random().toString(36).slice(2,8)`. Optionally, it allows you to add a prefix or postfix. |

