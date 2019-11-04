# 🔍 Description

build a simple image zoomer in vanilla javascript.


## Task

Look at `index.html`, you'll see 1 `img` tag in this file. Make this a zoomable image.

The business rules of this component:
* the image starts out normal (not zoomed in)
* clicking the image zooms in on the image where the click happened
* holding the mouse down and dragging pans around the image, still zoomed in.
* change the cursor to be a hand after you start dragging while zoomed in. `cursor: grabbing; cursor: -webkit-grabbing;`
* when releasing the mouse, stop dragging
* clicking on the image again returns to normal mode.


## Additional Constraints

* can use modules and libraries, but avoid doing this in any framework (react, vue, angular, etc.) Use vanilla javascript.
* assume modern javascript; internet explorer support isn't necessary.
* at least support mouse interactions (also supporting touch is a bonus)

## Hints
* thinking about the states that this component can be in is probably a good starting point and foundation for code structure


## Setup

1. clone this repo
2. `npm install`
3. `npm start` to run the server, then open a browser using the link provided in the command line output (it should also be copied to the clipboard automatically)
4. open `index.html` and hack away!


## Bonus Items

* support both mouse and touch interactions


## Timeframe

Take as long as you need, and submit when ready. That said, it shouldn't take a week to make this.

Good Luck! 🦄
