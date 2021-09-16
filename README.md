This is a sample project from unity with the [webgl-memory](https://github.com/greggman/webgl-memory)
hacked in.

The only changes are in `index.html` where a `setInterval` event is setup
for each context created by Unity. For some reason Unity creates both
a WebGL2 context and then abandons it and creates a WebGL1 context, at
least on my 2014 Mac. YMMV.

[Click here for example](https://greggman.github.io/webgl-memory-unity-example/)