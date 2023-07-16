# physicalgpt
in short: it works. ChatGPT was able to understand 3d space and perform semi advanced motions such as drawing an arc in space with the tip of a stick. the produced data is in /archive. if you want to try the data in archives, copy it to line 12 in index.html because i cant be bothered to make a proper example
### prompts:
```
calculate the rotations to apply to a stick to move it in a waving motion, similar to how humans wave. you may only rotate the stick around its center. respond in radians. the wave should take about 1 second at 10 frames per seconds. output must be formatted like: "x;y;z" for each step. do not respond with any words, ONLY THE SPECIFIED "x;y;z" format.
```
```
now "draw" a arc with the tip of the stick. this will require rotations on multi axis. make sure you rotate the stick on both the x and z axis. make the animation take 2 seconds at 10 frames per second. remember to respond in x;y;z format
```
