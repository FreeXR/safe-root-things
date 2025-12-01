## Rainbow draw_frame thing


the command (root not required):

```
while true; do draw_frame -r 255 & p=$!; sleep 1; kill $p; draw_frame -g 255 & p=$!; sleep 1; kill $p; draw_frame -b 255 & p=$!; sleep 1; kill $p; done
```

if you press ctrl+c and if the frame gets stuck on the screen then do:

```
draw_frame
```
and then ctrl+c again, if the frame persists reboot the headset i guess
