# First PAGE

There should be a top bar at the top side of the page. Color of bar is RGB(240,242,243). Also we need to have 2 buttons and 1 checkbox in that bar here according to following details;\
First Button,\
Color of button should be set to RGB(240,242,243) and color of text should be RGB(251,251,251) in css file. Text of button is "+New User". This button will be used to go page of adding new user. 

Second one is a checkbox. It should be at the right side of the first button. We need %3 padding here to seperate this two button. The text at the right side of button need to have color as black. The text is  "**Hide Disabled User**". Text and check box need to be in same div and padding should be for the outside of that div. If box is checked, button color should be set to RGB(55,122,181) and disabled user should be cleared from the table below. If the box unchecked, users should be appear in the table again.


Third button should be at the right side of the top bar if New User Page is opened and button color need to be set RGB(106,164,202) and color of text need to be set to RGB(251,251,251) in css file.



We need to have a table below the top bar, this table will show the datas as shown in the table below.
Top row of every column (title row) need to have color as RGB(55,122,181). If not selected a row need to have background as white. If a row selected, background color of that row need to change to RGB(188,214,228). 

ID | User Name | Email | Enabled  
| ----------- | ----------- | ----------- |  ----------- |
1 | AdminUser | admin@piworks.net | true
2 | TestUser | testuser@piworks.net | true



# NEW USER PAGE

This page will be used to add new user to database. The background of page need to be white and we need to have a top bar which has background color as RGB(240,242,243). At the top left corner of the bar, there should be a text as "New User" which has color as RGB(80,70,83).
We need to get 6 different datas from this page about user.

We need to get 4 datas from textfield:
1. Username
2. Display Name
3. Phone
4. Email

We need to get 1 data from dropdown multipe selection:
1. User Roles
Roles are Guest, Admin, SuperAdmin.  default background of selections is white, if user mouse over a selection (hover), background color of selection need to change to RGB(85,137,196)


We need to get 1 data from checkbox:
1. Enabled 
This data will be used in hide user function

