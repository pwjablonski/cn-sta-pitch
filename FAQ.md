# 📘 CN Lesson How To Guide 📘

This page will give you a brief overview of how to access, navigate, edit and share your CN Lesson.
CN Lesson Plans are made using [glitch](https://glitch.com/) and [reveal.js](https://github.com/hakimel/reveal.js/).
Each lesson plan is a self-contained repository including slides, and a lesson plan

## How do I access the instructor slideshow from my glitch project?

To view the instructor slideshow from your glitch project page simply press the `🕶️show` button at the top of your screen.
Then press `In a New Window`. You're all set!

## How do I access the student facing slideshow from my glitch project?

Click on the CN logo in the bottom left corner of any page on the instructor slides to open the actions panel.
Click on `Student Slides` to open the student facing slides. Alternatively you can navigate to `yourprojectname.glitch.me/students`. 

## What slide show features does reveal.js?

The slides also have some great presentation features you can take advantage of.

- **Speaker Notes** - Press `S` on the Keyboard to open up notes in a new window
- **Pause** - Press `B`on the Keyboard
- **Zoom** - Press `ctrl` on PC or `option` on Mac and click where you would like to Zoom
- **Print PDF** - From the actions panel click `View PDF`. This will open up a new window with a printer friendly version of the slide show

## How do I share lesson materials to google classroom?

Open the actions panel. You will be able share resources directly to Google Classrooms and automatically attach the resource URL
You can share...

- **Student Facing Slides** - Attaches the student facing slides at `yourprojectname.glitch.me/students`.
- **Lesson Resources** - Attaches the resources url listed in `lessonData.js`

## Can I share glitch project with my team to collaborate?

Yes! To share the lesson with you team click the `Share` button in the top left corner.
Copy the link under `Invite others to edit` and share the link with your teammates. Alternatively you can add the project
to a team you are all a part of.

## How do I make my own copy of the lesson to edit?

As you can probably already tell each lesson is its very own glitch project. What this means is we can view the source, remix/edit your own version!
To access the glitch project from your slide show simply click the glitch fish icon 🎏 in the top right corner of the page!

## How do I edit my slides?

Content for slides are written in a single markdown file called `SLIDES.md`.
Editing `SLIDES.md` will update teacher and student facing slides.
To edit your slide show's content open up the `SLIDES.md` file and click the `Markdown 👁️` button at the top of the file.
Forgot markdown syntax? Here's a great [Markdown Cheetsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) you can use.

Here are some additional reveal.js specific syntax for editing slides.

- **New Slide** - Add `---` padded by two blank lines. This will tell reveal to make new slide
- **Notes** - Anything written under `Note:` in a slide will be considered a note and will be hidden from view. You can still view notes in speaker view by pressing `S` on the keyboard.
- **Background** - Within the slide add `<!-- .slide: data-background="#000" -->` This works for images and gifs!
- **Fragment** - If you want to display elements on a slide sequentially next to the element add`<!-- .element: class="fragment" data-fragment-index="1" -->`
- **Code Block** - And code you want to show include it between two sets of three backticks with the correct language type

### Can I sync student slides to mirror the instructor slides?

To control students slides we have to establish a socket between the student facing slides
and the instructor slides.

1. Open index.html.js
2. Open go to [https://reveal-js-multiplex-ccjbegmaii.now.sh](https://reveal-js-multiplex-ccjbegmaii.now.sh) and generate a new token
3. Update the `socketData` object with the `secret` and `id` you just generated

All student facing Slides can now be controlled remotely from the instructor slide

## What else can Reveal.js do?

If you really really want to customize the slideshow settings please see [reveal.js documentation](https://github.com/hakimel/reveal.js/)
