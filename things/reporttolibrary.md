## Switches report menu to dock library


Enter a root shell:

```
adb shell
su
```

switch report menu to dock library with the following command as root:

```
pm disable-user --user 0 com.oculus.systemux/com.oculus.panelapp.bugreporter.BugReporterActivity
```

revert switch with the following command as root:

```
pm enable com.oculus.systemux/com.oculus.panelapp.bugreporter.BugReporterActivity
```
This persists across reboots and is safe to use.
