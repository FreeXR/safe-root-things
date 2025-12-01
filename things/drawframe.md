## Rainbow draw_frame thing

exit = ctrl + c (stops the current process)


the command (root not required):

```
while true; do draw_frame -r 255 & p=$!; sleep 1; kill $p; draw_frame -g 255 & p=$!; sleep 1; kill $p; draw_frame -b 255 & p=$!; sleep 1; kill $p; done
```

if you want to exit out of the loop then exit the process.
if the frame gets stuck then do:

```
draw_frame
```
and then exit again, if the frame persists reboot the headset i guess
