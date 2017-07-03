<h3>Information</h3>
This is a cordova plugin to use the Laser Barcode Scanner of Panasonic handhelds. Suported and tested devices:
<ul>
<li>A Panasonic toughpad FZ-N1 running Android</li>
</ul>

<h3>How to use</h3>

Activate the scanner and pass the success and error callback functions:

```
cordova.plugins.PanasonicScanner.activate({}, function(result) {
// each scan will trigger this callback function
}, function(error) {
// catch error on activation
});
```

<h3>License</h3>
Copyright 2017 Wouter Lemaire

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
