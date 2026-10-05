<h1 align="center">Dinner With Grandpa</h1>
<p align="center"><i>An interactive animated storybook, adapted from "Rabbit Stew"</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.1.0-8038C5?style=flat-square" alt="version">
  <img src="https://img.shields.io/badge/status-complete-2772BD?style=flat-square" alt="status">
  <img src="https://img.shields.io/badge/Google%20Web%20Designer-16.3-2B9580?style=flat-square&logo=google&logoColor=white" alt="Google Web Designer">
  <img src="https://img.shields.io/badge/HTML5-browser-E59A18?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/content-warning-CA2A44?style=flat-square" alt="content warning">
</p>

<p align="center">
  <a href="https://youtu.be/_9GphO3P6es" target="_blank" rel="noopener noreferrer"><strong>Video Preview</strong></a> ·
  <a href="#read-the-storybook">Read the Storybook</a> ·
  <a href="#edit-the-project">Edit the Project</a> ·
  <a href="#project-structure">Project Structure</a> ·
  <a href="https://github.com/nncast/GoogleWebDesign-Storybook/releases" target="_blank" rel="noopener noreferrer">Release Notes</a>
</p>

**Dinner With Grandpa** is an interactive, animated picture-book adaptation of the short story ["Rabbit Stew"](https://www.scaryforkids.com/rabbit-stew/), designed and built in **Google Web Designer**.
It started as a UI/UX exercise in interactive design and grew into a 70-page illustrated story. With the title, settings, credits and ending screens, the full page deck has 150 pages, each with its own animation, music and sound.

> **Current version: v0.1.0**, the first release (June 2024). See the [Release Notes](https://github.com/nncast/GoogleWebDesign-Storybook/releases) for details.

> **Content warning:** this storybook contains death, graphic violence, a suggestive reference to cannibalism, and **flashing lights**. The same warning is shown before the story begins.

<p align="center">
  <img src="https://github.com/user-attachments/assets/64089ab8-cdd7-409a-9305-503c72e37048" width="49%" alt="Storybook screenshot 1">
  <img src="https://github.com/user-attachments/assets/d8573c7b-8bea-42e9-9be7-c3e754592efe" width="49%" alt="Storybook screenshot 2">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/bbbb2d63-d67e-4040-b08d-0e73778dcfed" width="49%" alt="Storybook screenshot 3">
  <img src="https://github.com/user-attachments/assets/ee551d0b-95a3-4856-ab8b-e658aa929791" width="49%" alt="Storybook screenshot 4">
</p>

<p align="center"><sub>Screens from the storybook. Watch the <a href="https://youtu.be/_9GphO3P6es">video preview</a> to see the animation and sound.</sub></p>

## Features

- **70-page illustrated story**, with animated transitions between pages
- **Tap navigation:** Next and Previous on every page, plus a Home button to return to the title screen
- **Soundtrack and sound effects:** background music and ambient sound (birds, a ticking clock, a kitchen, a passing car, wind) that change with the scene
- **Settings screen** with a sound on/off toggle
- **Content warning** before the story, plus **Credits** and a **Replay** option at the end
- Runs in the browser, with no install needed to read it

## Read the storybook

You don't need Google Web Designer just to read it.

1. Get the files: click **Code → Download ZIP** on this page and extract it, or clone the repository:
   ```bash
   git clone https://github.com/nncast/GoogleWebDesign-Storybook.git
   ```
2. Open `gwd_preview_Storybook_Demo/index.html` in **Google Chrome**.
3. Turn your sound on, then tap or click to start.

An internet connection is needed for the fonts, which load from Google Fonts.

## Edit the project

1. Install [Google Web Designer](https://webdesigner.withgoogle.com/) (built with version 16.3).
2. Open `Storybook_Demo.html` in Google Web Designer.
3. To test your changes, click **Preview** in the top-right corner and choose **Chrome**.

## Project structure

| Path | What it is |
|---|---|
| `Storybook_Demo.html` | The Google Web Designer source document. Open this one to edit. |
| `assets/` | Illustrations, music and sound effects used by the source document |
| `gwd_preview_Storybook_Demo/` | Latest browser build, with its own copy of the assets. Open `index.html` to read the story. |
| `Storybook_Demo/` | An earlier published build from June 2024 |
| `gwd*_min.js`, `gwd*_style.css` | Google Web Designer component runtime: page deck, tap areas, audio, gallery and so on |

## Credits

- **Original story:** "Rabbit Stew," from [Scary For Kids](https://www.scaryforkids.com/rabbit-stew/)
