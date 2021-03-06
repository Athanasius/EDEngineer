# EDEngineer

EDEngineer is a basic app I've written to track materials, data and cargo acquired in Elite Dangerous. That way, we can also track progress of blueprints available from the Engineers.

##### **Warning:** Elite Dangerous started outputting logs only recently. It's very probable that the initial state of the app is wrong (negative numbers, missing entries, wrong numbers...) so you will have to manually change the quantities using the +/- buttons. These manual changes are recorded so you don't have to do it each time you start the app. After that, you are not supposed to use these +/- buttons.

![Overview](http://i.imgur.com/lOsjnfe.png)

### Install

Install the [setup.exe](https://cdn.rawgit.com/msarilar/EDEngineer/master/EDEngineer/releases/setup.exe) which will download the published application on github (it will check for update each time the application is started). Launch the game in windowed mode, launch EDEngineer. Change the shortcut if ctrl+F10 does not suit you (right click the tasktray icon to do so) and fix the cargo/materials/data numbers (by comparing counters one by one ; it's kind of tedious I agree, but it's a one time only operation!).

### Features

1. A transparent overlay that runs continuously and updates in real time what your ship holds (based on logs outputted by the game)
2. Automatically finds the log folder ; you can change it by clicking on the path (bottom of the overlay)
3. Show/Hide the overlay based on a global shortcut (default is Control + F10)
4. A tray icon where you can configure the shortcut and exit the overlay
5. All blueprints available in a handy sortable grid which you can filter too
6. Ignore/Favorite flags - Favorited blueprints that become available to craft trigger a Windows toast
7. Persistent state : EDEngineer will remember which filters you applied and what blueprints are favorited/ignored

### Additional Screenshots

![Details](http://i.imgur.com/FW4jNHG.png)

![Filters](http://i.imgur.com/yRdCYCs.png)

![Toast](http://i.imgur.com/td5H0OW.png)

![Tray Icon](http://i.imgur.com/HEjjjV6.png)