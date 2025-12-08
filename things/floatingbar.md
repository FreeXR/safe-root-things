## Floating Bar under app


Enter a root shell:

```
adb shell
su
```

disable floating bar under app with the following command as root:

>=v77 i think
```
pm disable-user --user 0 com.oculus.vrshell/com.oculus.panelapp.controlbar.ControlBarActivity
```
<v77 i think
```
pm disable-user --user 0 com.oculus.vrshell/com.oculus.panelapp.controlbar.ControlBarPanelService
```
re-enable floating bar under app with the following command as root:

>=v77 i think
```
pm enable com.oculus.vrshell/com.oculus.panelapp.controlbar.ControlBarActivity
```
<v77 i think
```
pm enable com.oculus.vrshell/com.oculus.panelapp.controlbar.ControlBarPanelService
```
This persists across reboots and is safe to use.
