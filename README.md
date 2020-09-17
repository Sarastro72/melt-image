# melt-image

Sorts the pixels of an image in two dimensions based on the properties of the colors.

Usage: 
1. Clone repository
2. Start (or make accessible through) a webserver. For example run command `php -S 127.0.0.1:1338` or `python3 -m http.server 1338`
3. Open in browser `http://localhost:1338?i=strawberry.jpg`. You can choose any image in the directory.
4. Adjust the parameters to you liking. The first row determines sorting on the X-axis and the second row Y-axis. The parameters are in order: `Hue` (color of the rainbow), `Saturation` (colorful or B/W), `Value` (brightness)
5. Hit the `Run` button.

Hint, You can change the parameters at any time and hit the `run` button again to use the new values.

Try it out: https://sarastro72.github.io/melt-image/index.html?i=sthlm.jpg&p=[0,10,10,0,-10,0,0,0,0]
