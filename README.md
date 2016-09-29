# TabControl Example App

This app demonstrates the TabControl in its current state. Some default tabs are configured, but the app provides buttons for adding, removing, and inserting tabs.

Clicking on a tab will select the tab, and print the argument passed to the click handler (the selected tab's model) out to the screen. 

Tabs can also be scrolled using the previous and next buttons at either end of the tab bar.

## Installation

1. Download the app, unzip it, and move it to your workspace folder.
2. Switch to the **master** or **cadence-release** branch in ividev.
3. Select 'tab control' from the launch app/workspace menu in the simulator.

## Tips

* The insert tab button currently inserts all tabs into the 2nd position in the tab bar. This can be updated to be any position in the click handler for the insert tab button in the app view.
* The remove tab button will always remove the last tab in the tab bar. This can be updated to remove any tab in the click handler for the remove tab button in the app view.
