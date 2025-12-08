## Enable Hulk UI


Enter a root shell:

```
adb shell
su
```

Enable Hulk UI with the following command as root:

```
oculuspreferences --setc ocui_hulk_ui_enabled true
am force-stop com.oculus.vrshell
```

Disable Hulk UI with the following command as root:

```
oculuspreferences --setc ocui_hulk_ui_enabled false
am force-stop com.oculus.vrshell
```
This persists across reboots and is safe to use.
