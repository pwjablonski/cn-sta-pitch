# 📘 CN Lesson How To Guide 📘

This page will give you a brief overview of how to access, navigate, edit and share your CN Lesson

## Overview

CN Lesson Plans are made using [glitch](https://glitch.com/) and [reveal.js](https://github.com/hakimel/reveal.js/).
Each lesson plan is a self-contained repository including slides, and a lesson plan

## Lesson Plan

Open up the `README.md` file. The lesson plan will detail Teacher Prep, Resources, Potential Misconceptions

## Accessing the Slide Show

To view the slide show from your glitch project page simply press the `🕶️show` button at the top of your screen. Then press `In a new window`. You're all set!

## Using the Slide Show

You've got this! Just use the key board arrows or the arrows in the bottom right corner to flip through the slides.
The slide show also has some great presentation features you can take advantage of.

- **Speaker Notes** - Press `S` on the Keyboard
- **Pause** - Press `B`on the Keyboard
- **Zoom** - Press `ctrl` on PC or `option` on Mac and click where you would like to Zoom

## CN Actions

To access the CN Actions simply click on the CN logo in the bottom left corner of any page.

- **Share to Classroom** - This will open Google Classrooms sharing interface and will aumatically attach the current slide show's URL
- **Print PDF** - This will open up a new window with a printer friendly version of the slide show

## Glitch Features

As you can probably already tell each lesson is its very own glitch project. What this means is we can view the source, remix/edit your own verision!
To access the glitch project from your slide show simply click the glitch fish icon in the top right corner of the page!

## Editing Your Slide Show

Content for slides are written in a single markdown file called `SLIDES.md`.
To edit your slide show's content open up the `SLIDES.md` file and click the `Markdown 👁️` button at the top of the file.
Always forgetting markdown syntax? Here's a great [Markdown Cheetsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) you can use.

- **New Slide** - Add `---` padded by two blank lines. This will tell reveal to make new slide
- **Background** - Within the slide add `<!-- .slide: data-background="#000" -->` This works for images and gifs!
- **Fragment** - If you want to display elements on a slide sequentially next to the element add`<!-- .element: class="fragment" data-fragment-index="1" -->` 
- **Code Block** - And code you want to show include it between two sets of three backticks with the correct language type


## Advanced Reveal.js
If you really really want to customize the slideshow settings please see [reveal.js documentation](https://github.com/hakimel/reveal.js/)
