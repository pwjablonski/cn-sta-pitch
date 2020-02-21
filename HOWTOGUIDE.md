# CN Lesson Show How To Guide

This page will give you a brief overview of how to access, navigate, edit and share your CN Lesson


## Overview

CN Lesson Plans are made using [glitch](https://glitch.com/) and [reveal.js](https://github.com/hakimel/reveal.js/).
Each lesson plan is a self-contained repository including slides, materials and lesson plans

## Accessing Slide Show

To view the slide show in a new tab press the `show` button at the top of your screen then press `In a new window`. You're all set!

## Using the Slide Show

Reveal.js has some great formating and features that included out of the box.
Just use the key board arrows or the arrows in the bottom right corner to flip through slides.

## CN Actions
To access the CN Actions simply click on the 
- **Share to Classroom** - This will open Google Classrooms sharing interface and will aumatically attach the current slide show's URL to what ever 
- **Print PDF** - This will open up a new window with a printer friendly version of the slide show

### Shortcuts
- **Speaker Notes** - Press `S` on the Keyboard
- **Pause**  - Press `B`on the Keyboard
- **Zoom** - Press `ctrl` on PC or `option` on Mac and click where you would like to Zoom


## File Structure
Let's take a look a what we've got!

```
.
├── _reveal
├── HOWTOGUIDE.md
├── README.md
├── SLIDES.md
├── index.html
```

**reveal** - This is the folder containing reveal.js files. You shouldn't be editing this.

**HOWTOGUIDE.md** - You're already here!

**README.md** - This is the primary teacher facing lesson plan

**SLIDES.md** - This where we write the content for the slides in markdown

**index.html** - This where we configure and serve the slide show. You shouldn't be editing this either :)






If you really want to customize the slideshow settings please see [reveal.js documentation](https://github.com/hakimel/reveal.js/)