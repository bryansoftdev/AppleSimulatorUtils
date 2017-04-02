# AppleSimulatorUtils
A collection of Apple simulator utils

```shell
Usage: applesimutils --simulator <simulator identifier> --bundle <bundle identifier> --setPermissions "<permission1>, <permission1>, ..."
       applesimutils --simulator <simulator identifier> --restartSB

Options:
    --simulator        The simulator identifier
    --bundle           The app bundle identifier
    --setPermissions   Sets the specified permissions and restarts SpringBoard for the changes to take effect
    --restartSB        Restarts SpringBoard
    --help, -h         Prints usage

Available permissions:
    calendar=YES|NO
    camera=YES|NO
    contacts=YES|NO
    health=YES|NO
    homekit=YES|NO
    medialibrary=YES|NO
    microphone=YES|NO
    motion=YES|NO
    notifications=YES|NO
    photos=YES|NO
    reminders=YES|NO
    siri=YES|NO
```