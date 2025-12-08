# safe-root-things
This repository contains a list of safe root things to do.
| Link to file | Description | Supported devices | Requirements | How to run
|--------------|--------------|---------------------|------------|--------|
| LED |
| [**Rainbow led**](https://github.com/FreeXR/safe-root-things/blob/main/things/colours.sh) | Cycles the device LED through rainbow colors | eureka/panther | UID0/SELinux Permissive? | Push → `chmod +x` → execute
| [**Power Indicator LED**](https://github.com/FreeXR/safe-root-things/blob/main/things/powerindicatorled.sh) | LED changes color based on battery charge level | eureka/panther | UID0/SELinux Permissive? | Push → `chmod +x` → execute
| Navigator/Dock |
| [**Navigator Fog**](https://github.com/FreeXR/safe-root-things/blob/main/things/navigator_background_fog.md) | Toggles background fog in Navigator | eureka/panther | Root Shell, Navigator | `adb shell`
| [**Dock Editor**](https://github.com/Lumince/DockEditor) | Full dock customization editor | eureka/panther | UID0, Magisk, Dock | install as apk
| [**Rebootless UI Switching**](https://github.com/FreeXR/safe-root-things/blob/main/things/rebootlessuiswitching.md) | Toggle between Navigator and Dock without rebooting | eureka/panther | Root Shell | `adb shell`
| Panel Behavior |
| [**Fixed Panel Scaling**](https://github.com/FreeXR/safe-root-things/blob/main/things/fixed_panels.md) | Locks or unlocks panel size adjustment | eureka/panther | Root Shell | `adb shell`
| [**Infinite Floating Panels**](https://github.com/FreeXR/safe-root-things/blob/main/things/infinitefloatingpanels.md) | Toggles unlimited floating panels | eureka/panther | Root Shell | `adb shell`
| [**Floating Bar**](https://github.com/FreeXR/safe-root-things/blob/main/things/floatingbar.md) | Enables / disables the floating bar under apps | eureka/panther | Root Shell | `adb shell`
| [**Hulk UI**](https://github.com/FreeXR/safe-root-things/blob/main/things/hulkui.md) | Enables / disables the Hulk UI coloring | eureka/panther | Root Shell | `adb shell`
| VR Behavior |
| [**Teleport Anywhere**](https://github.com/FreeXR/safe-root-things/blob/main/things/disable_teleport_limit_in_home_environment.md) | Removes teleport restrictions in the home environment | eureka/panther | Root Shell | `adb shell`
| [**No Controller Requirement**](https://github.com/FreeXR/safe-root-things/blob/main/things/nocontrollerjoin.md) | Toggles joining VR apps with or without controllers | eureka/panther | Root Shell | `adb shell`
| [**Void Transition**](https://github.com/FreeXR/safe-root-things/blob/main/things/voidtransition.md) | Toggle between Immersive transition and Void Transition | eureka/panther | Root Shell | `adb shell`
| [**Replace Report Keybind**](https://github.com/FreeXR/safe-root-things/blob/main/things/reporttolibrary.md) | Changes report menu keybind to the dock library | eureka/panther | Root Shell | `adb shell`
| Utilites/Info |
| [**Dogfood Hub**](https://github.com/FreeXR/safe-root-things/blob/main/things/dogfood_hub.md) | Enables Dogfood Hub | eureka/panther | Root Shell | run in adb
| [**Get Controller Info**](https://github.com/FreeXR/safe-root-things/blob/main/things/controllerinfo.md) | Retrieves detailed controller information | eureka/panther | Shell | `adb shell`
| [**Rainbow draw_frame**](https://github.com/FreeXR/safe-root-things/blob/main/things/drawframe.md) | Make your headset screen go rainbow | eureka/panther? | Shell | `adb shell`
