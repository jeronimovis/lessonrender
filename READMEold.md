<p align="center">
  <a href="https://jeronimovis.github.io/lessonrender/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/logo/dropcap-classic-dark.svg">
      <img src="assets/logo/dropcap-classic-light.svg" alt="LessonRender" width="380">
    </picture>
  </a>
</p>

<h3 align="center">Turn anything into an interactive English lesson.</h3>

<p align="center">
Choose your own text or a YouTube video script. A free AI writes the exercises,<br>
and LessonRender builds a page your students can use in class, at home or on their phones.
</p>

<p align="center">
  <a href="https://jeronimovis.github.io/lessonrender/"><img src="assets/buttons/visit-website.svg" alt="Visit the website" width="280"></a>
  <a href="https://jeronimovis.github.io/lessonrender/lessons/house-tour/"><img src="assets/buttons/try-lesson.svg" alt="Try a finished lesson" width="280"></a>
  <a href="https://github.com/jeronimovis/lessonrender/raw/main/assets/starter-kit.zip"><img src="assets/buttons/download-kit.svg" alt="Download the starter kit" width="280"></a>
</p>

<p align="center">
  <a href="https://jeronimovis.github.io/lessonrender/lessons/house-tour/">
    <img src="assets/lesson-preview.png" alt="A LessonRender lesson: a video clip, true or false questions with Check, Show and Clear buttons, and the Appearance menu with six styles" width="820">
  </a>
</p>

---

## Start here

1. **[Make a lesson from your own materials.](https://jeronimovis.github.io/lessonrender/#materials)**
   A super fast lesson from any material: give an AI your texts, photos or links with the flash kit.
2. **[Make a lesson from a YouTube video.](https://jeronimovis.github.io/lessonrender/#youtube)**
   Everything happens online, with free AI assistants. About 15 minutes.
3. **[Use your own audio or video.](https://jeronimovis.github.io/lessonrender/#own)**
   Download the starter kit, drop in your recordings and open the lesson.
4. **[See a finished lesson.](https://jeronimovis.github.io/lessonrender/lessons/house-tour/)**
   A 45-minute C1 lesson about a house on the Murray River.

The website takes you through each path step by step, with pictures.

## What your students get

- **Clips that start and stop where you choose**, from YouTube, MP3 or MP4.
- **Fifteen kinds of activity** that check themselves: gaps, true or false, multiple choice, matching, ordering, word formation and more.
- **Help when they're stuck**: a word bank to open, and an answer key at the end.
- **Reading texts, images, timers**, useful-language boxes and role cards.
- **Six looks**, light and dark, on phones, projectors and paper.

And for you: teacher's notes, folded away at the bottom of the page.

## A lesson is a text file

This is part of the starter kit's demo lesson. Change a word, save, reload, and the page changes with it.

```
## Watch | Individual · 4 minutes
> Watch the video. Are the sentences true or false?

[play video.mp4 "The video"]

[tf] You can use your own audio and video files instead of these ones. [t]
[tf] YouTube videos play well when you open the lesson from your computer. [f]
```

Teachers write lessons by hand in Notepad or TextEdit, or ask an AI to write them with the prompts in [`ai/`](ai/).

## Examples

- **[House tour](https://jeronimovis.github.io/lessonrender/lessons/house-tour/)**: a complete C1 lesson for architects, made from a YouTube house tour.
- **[Feature guide](https://jeronimovis.github.io/lessonrender/lessons/feature-guide/)**: a lesson about the engineering of Venice that shows every activity, with how each one is written.

## Downloads

- **[Flash kit](https://github.com/jeronimovis/lessonrender/raw/main/assets/starter-kit-flash.zip)**: a super fast lesson from any material. Attach your texts, images, links or transcripts to an AI with the prompt and `SKILL.md`, then open the lesson in LessonRender online.
- **[Starter kit](https://github.com/jeronimovis/lessonrender/raw/main/assets/starter-kit.zip)**: the page, a demo lesson, a short audio and video, and the AI files.
- **[AI files](ai/)**: the four prompts and `SKILL.md`, which teaches any AI assistant the LessonRender format.

## For the curious

- **[Reference](https://jeronimovis.github.io/lessonrender/assets/LessonRender-reference.html)**: every tag and option, with examples to copy.
- **[Specification](assets/LessonRender-spec.md)**: the complete notation, written for AI assistants.
- **How it works**: one HTML file reads the lesson text and builds the page inside the browser. It works on any static host, or straight from a folder on your computer. The only outside resources are Google Fonts and, for YouTube clips, the YouTube player.

```
lessonrender/
├── index.html      the website
├── online/         LessonRender online: paste or open any lesson
├── lessons/        house-tour/ and feature-guide/
├── starter-kit/    the files inside starter-kit.zip
├── ai/             prompts and SKILL.md
└── assets/         logo, screenshots, starter-kit.zip, reference, specification
```

## Licence

[MIT](LICENSE). Free to use, change and share.

Made by [Jerónimo Visñovezky](https://jeronimov.org), English teacher.
