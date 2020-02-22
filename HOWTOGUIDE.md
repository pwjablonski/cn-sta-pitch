# 📘 CN Lesson How To Guide 📘

This page will give you a brief overview of how to access, navigate, edit and share your CN Lesson

## Overview

CN Lesson Plans are made using [glitch](https://glitch.com/) and [reveal.js](https://github.com/hakimel/reveal.js/).
Each lesson plan is a self-contained repository including slides, and a lesson plan

## Lesson Plan

Open up the `README.md` file. The lesson plan will detail Teacher Prep, Resources, as well as Potential Misconceptions

## Accessing the Slide Show

To view the slide show from your glitch project page simply press the `🕶️show` button at the top of your screen. Then press `In a New Window`. You're all set!

## Navigating the Slide Show

Just use the key board arrows or the arrows in the bottom right corner to flip through the slides.
The slides also have some great presentation features you can take advantage of.

- **Speaker Notes** - Press `S` on the Keyboard
- **Pause** - Press `B`on the Keyboard
- **Zoom** - Press `ctrl` on PC or `option` on Mac and click where you would like to Zoom

## CN Actions

To access the CN Actions simply click on the CN logo in the bottom left corner of any page.

- **Share to Classroom** - This will open Google Classrooms sharing interface and will aumatically attach the current slide show's URL
- **Print PDF** - This will open up a new window with a printer friendly version of the slide show

## Glitch Features

As you can probably already tell each lesson is its very own glitch project. What this means is we can view the source, remix/edit your own verision!
To access the glitch project from your slide show simply click the glitch fish icon 🎏 in the top right corner of the page!

## Editing Your Slide Show

Content for slides are written in a single markdown file called `SLIDES.md`.
To edit your slide show's content open up the `SLIDES.md` file and click the `Markdown 👁️` button at the top of the file.
Forgot markdown syntax? Here's a great [Markdown Cheetsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) you can use.

- **New Slide** - Add `---` padded by two blank lines. This will tell reveal to make new slide
- **Notes** - Anything written under `Note:` in a slide will be considered a note and will be hidden from view. You can still view notes in speaker view by pressing `S` on the keyboard.
- **Background** - Within the slide add `<!-- .slide: data-background="#000" -->` This works for images and gifs!
- **Fragment** - If you want to display elements on a slide sequentially next to the element add`<!-- .element: class="fragment" data-fragment-index="1" -->`
- **Code Block** - And code you want to show include it between two sets of three backticks with the correct language type

### Updating Project Links

To update projects links open up the `lessonData.js`
This will update the `href` for any link with a corresponding class in `SLIDES.md`
I.E.

- Updating url here...
  - `{ IP: "https://popcode.com"}`
- will update all the links with the class `"IP"`
  - `<a target="_blank" class="IP">Independent Practice</a>`

## Advanced Reveal.js

If you really really want to customize the slideshow settings please see [reveal.js documentation](https://github.com/hakimel/reveal.js/)
