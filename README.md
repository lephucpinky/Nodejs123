QUESTION 1:

1. Complete the creating task & marking as done behavior: 
- When user create a task with form submission, The list should be updated with new created entry.
- When user click the checkbox, item's status should be updated to "done" / "not finished"
  And the total number of undone tasks on top should be updated.

2. Show the not finished tasks only 

- Create a checkbox on top, saying "Not finished only". When it's checked, we show only the going tasks only.
- When it's unchecked, we show both done and not finsished tasks.
- Find a way to use URL to fast access the going tasks. For example: `<app-domain.com>?withDone=1` for getting all tasks (done tasks included)

3. Store all the tasks permantly and load them in the first place. 

All the task should be storaged inside the LocalStorage. When user first come to the app, we load everything from storage to the app.

4. Attach a due date to a task 

A task could have a due date for reminding later. Storage this information and show how many day left until the due date on each item.

5. Languague switching 

Change the UI language with the language switcher

Please work with Codesandbox: https://codesandbox.io/s/xcareer-lv-3-test-8q4yxg?file=/src/App.js

=>
My sandbox link:
https://codesandbox.io/s/xcareer-lv-3-test-forked-lw9ljn
