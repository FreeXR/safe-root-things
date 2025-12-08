## Disable need for controllers when joining VR game


Enter a root shell:

```
adb shell
su
```

disable controller requirement with the following command as root:

```
oculuspreferences --setc vrshell_skip_launchcheck_requires_controllers_enabled true
```

re-enable controller requirement with the following command as root:

```
oculuspreferences --setc vrshell_skip_launchcheck_requires_controllers_enabled false
```
This persists across reboots and is safe to use.
