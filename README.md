# melt-image

Sorts the pixels of an image in two dimensions based on the properties of the colors.

Usage: 
1. Clone repository
2. Start (or make accissble through) a webserver. For example run command `php -S 127.0.0.1:1338` or `python -m SimpleHTTPServer 1338`
3. Open in browser `http://localhost:1338?i=strawberry.jpg`. You can choose any image in the directory.
4. Adjust the parameters to you liking. The first row determines sorting on the X-axis and the second row Y-axis. The parameters are in order: `Hue` (color of the rainbow), `Saturation` (colorful or B/W), `Value` (brightness)
5. Hit the `Run` button.

Hint, You can change the parameters at any time and hit the `run` button again to use the new values.