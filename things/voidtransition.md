## Transition


Enter a root shell:

```
adb shell
su
```

Enable Immersive Transition:

```
oculuspreferences --setc shell_immersive_transitions_enabled true
am force-stop com.oculus.vrshell
```

Enable Void Transistion

```
oculuspreferences --setc shell_immersive_transitions_enabled false
am force-stop com.oculus.vrshell
```
This does not persist across reboots and is safe to use.
