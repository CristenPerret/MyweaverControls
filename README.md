# MyweaverControls
Currently its just an `AHK` that can openendly be given bind keys to perform actions.

It will only apply to anything named 'Skyweaver.exe' but can easily work in-browser.

Hotkeys are saved & stored in an `.ini` file where this `.ahk` file resides.

Once running you can either press **"F8"**, or select the 'Keybinds' option in your Tray to setup your binds.
___
###### Your options are the functions listed below, or feel free to have it do anything you want it to do as your copy is your copy.



### Functions
```
Grabscreenregion() - When bound to a hotkey it will save your cursor position when pressed to your clipboard. In the syntax this code likes.
GG() - Will Concede and interact with the nessisary things to requeue.
OpenMenu() - Clicks on the button for the in-game settings.
PassTurn() - Ends your turn and returns the mouse back where it was .
HandCont() - Moves mouse to the Continue button or in the center where your hand resides.
```
# Next to be added
1. Emotes 	:lying_face:
2. Smorc



### Customizing the script
* To adjust the quantity of hotkeys change `#actions = 6` Found at the very top.
* To change the text that appears next to each hotkey edit `ActionTitle :=[]` Found just below `#actions = #`. 
* Assigning actions to the hotkeys are found at the very end of the script. Starting at `Action1:`
__
#### If theres any problems with the alignment of the binds
add `GrabScreenRegion()` in one of the 'Action' areas of the very bottom of the Script.

Once the bind for this function is used, it will save in the proper syntax for this code in your clipboard the data from where your cursor was relative to the Skyweaver Window. `:= GAP(x.xx, y.yy)`

