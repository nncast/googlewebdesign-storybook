# Contributing to Dinner With Grandpa

Thanks for helping out. Fixes to the story's text, timing, sound or navigation are all welcome.

## Reporting bugs and ideas

Open an [issue](https://github.com/nncast/googlewebdesign-storybook/issues) with:

- the page number (or the screen: title, settings, credits, ending) and what you did
- what you expected, and what happened instead; a screenshot or short screen recording helps with animation problems
- your browser and device

Security problems do not go in issues; see [SECURITY.md](SECURITY.md).

## Setting up

Install [Google Web Designer](https://webdesigner.withgoogle.com/) (the project was built with version 16.3) and open `Storybook_Demo.html`, as in [Edit the project](README.md#edit-the-project).

## Making a change

1. Fork the repository and create a branch from `main` (for example `fix-page-12-audio`).
2. Keep each pull request to one fix or feature.
3. Click **Preview** → **Chrome** and go through every page you changed, with the sound on and off (**Settings**).
4. Open a pull request that says what changed and on which pages. Screenshots or a short recording help.

## Guidelines

- Edit the story in Google Web Designer, not by hand in the HTML, so `Storybook_Demo.html` still opens there.
- Put new illustrations, music and sound effects in `assets/`, and keep them small: the whole story loads in the browser.
- Use only art and audio you are allowed to share, and credit it in the README.
- If a change adds violence, flashing lights or other upsetting content, update the content warning in the story and in the README.
- Do not edit the Google Web Designer runtime files (`gwd*_min.js`, `gwd*_style.css`).
- If readers should see your change, update the browser build in `gwd_preview_Storybook_Demo/` from Google Web Designer and include it in the pull request.
