## Rainbow draw_frame loop

Enter the shell:

```
adb shell
```

The Rainbow Loop

```
while true; do draw_frame -r 255 & p=$!; sleep 1; kill $p; draw_frame -g 255 & p=$!; sleep 1; kill $p; draw_frame -b 255 & p=$!; sleep 1; kill $p; done
```

Exit out of the loop

```
(ctrl + c)
draw_frame
(ctrl + c)
```
This does not persist across reboots and is safe to use. If the frame persists however after exiting out of the loop then exit out again except skip the first key combo
