# DisableIndustrialConveyors
Gives chat command to turn all conveyors off and will forcefully disable conveyors if save file is nearly full.
The issue is that each transfere of a conveyor uses up another network id which is easy to run out of on a large server.

Chat Command: (needs admin)
/conveyorsoff switches every ones conveyor off to help slow the net id bleed.

It will auto disable the conveyors transfering if the save file reaches 95% full to stop server crashing.
