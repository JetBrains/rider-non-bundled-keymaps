If you find inaccuracies or missing shortcuts, please help improving the keymaps in one of the follwoing ways:
* Log a new [issue](https://github.com/JetBrains/rider-non-bundled-keymaps/issues)
* Update a keymap yourself

Updating kyemaps
----------------
1. [Install](https://github.com/JetBrains/rider-non-bundled-keymaps/blob/master/README.md) the keymap that you want to update.
2. Open the **Keymap** page of Rider settings and choose the installed keymap.
3. Find the action for which you want to fix the shortcut. Make sure that you choose the correct action as actions (or commands) 
performing the same things in different products can be named differently. 
If unsure, it's better to log a new [issue](https://github.com/JetBrains/rider-non-bundled-keymaps/issues).
5. Assign the desired shortcut to the selected action (right-click, Add keyboard shortcut, press the keystroke).
4. Check whether the shortcut that you are assigning is already assigned to another action - 
you can search actions by the shorcut on the **Keymap** settings page.
If it is assigned incorrectly, remove it (right-click, Remove).
Note that some actions are only available in limited scopes (e.g. in a tool window) - 
in this case it may be safe to leave the same shortuct assigned on several different actions.
6. Save the settings and make sure that the newly assigned shortcut works as expected.
5. You can find the modified keymap file (.xml) in:
  * *Windows* `%USERPROFILE%\.RiderXX\config\keymaps`
  * *macOS* `~/Library/Preferences/RiderXX/keymaps`
  * *Linux* `/home/user/RiderXX/config/keymaps`
7. Use the modified keymap file to update the corresponding 
[keymap file in the repository](https://github.com/JetBrains/rider-non-bundled-keymaps/tree/master/src).
8. We will review you changes and add them to the next release of non-bundled keymaps.
