![CS1 Game Engine](https://cdn.glitch.com/b66cc221-adcc-4cb2-beb1-63719002f3fa%2FCS1_logo_64.png?v=1589228401221)
# CS1 Game Engine Shader Editor

### based upon work by <a href="http://shawnlawson.com" rel="noopener noreferrer">Shawn Lawson</a>.
___

## API
If you're looking for which functions are built-in, then give the wiki [API](https://github.com/shawnlawson/The_Force/wiki/API) a look.

### Additionally helpful to know

- [The_Force/shaderExperiments](./shaderExperiments) contains several examples to get you started
- [Workshop Notes](https://github.com/shawnlawson/The_Force_Workshop) contains some hand-written information and a few more example shaders
- [The_Force/help](./help) contains helpful documents, including **instructions to run local/offline (it's easy!)**
- line in and microphone only work in Google Chrome, and requires HTTPS
- **CTRL + SHIFT** will toggle text visibility
- backbuffer is a copy of the previous frame's frontbuffer
- 512 fft in row 0; waveform in row 1
- keyboard data in row 0 of texture (`channel0`) - not recently tested
- open file is not totally safe; it's only checking for filename extension ".frag"
- images save as .png

## Sources

* https://github.com/ajaxorg/ace
* http://darsa.in/fpsmeter/ also https://github.com/darsain/fpsmeter
* http://jquery.com
* http://www.flaticon.com
* https://github.com/eligrey/FileSaver.js
* https://github.com/eligrey/canvas-toBlob.js
* https://github.com/marmorkuchen-net/osc-js
