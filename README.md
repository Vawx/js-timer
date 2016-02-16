# JavaScript Timer

## Description
A timer to use instead of setInterval that will only trigger when it has completed and wont be interfered with with repetitive input.

## Use
`new Timer( timeInMilliseconds, functionCallBack, timerName )`

1. timeInMilliseconds : The time the timer will run for before calling the function call back
2. functionCallBack : The function that is called when the timer is complete
3. timerName : String name of timer. Does not have to be unique but probably should be if you want a reference back for it by name.

Use `index.html` and `timer.js` for example.

## License
Copyright (c) <2016>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.