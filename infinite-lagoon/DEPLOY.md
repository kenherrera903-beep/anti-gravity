# Deployment Guide - Cucina Design Studios

This website is a static site (HTML, CSS, JS), which makes it very easy and free to host on modern platforms. Here are the best ways to deploy it.

## Option 1: Netlify Drop (Easiest - No Account Setup Required initially)

1.  Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2.  Open your file explorer on your computer.
3.  Locate the folder: `/Users/kenherrera522/.gemini/antigravity/playground/infinite-lagoon`.
4.  Drag and drop the entire `infinite-lagoon` folder onto the Netlify page.
5.  Netlify will instantly upload and give you a live URL (e.g., `silly-name-12345.netlify.app`).
6.  You can claim the site to change the name or add a custom domain later.

## Option 2: Vercel (Fast & Professional)

1.  If you have Node.js installed, you can use the terminal.
2.  Run `npx vercel` inside the project folder.
3.  Follow the prompts (Log in -> Set up and deploy -> Yes to strict defaults).
4.  Your site will be live at a `vercel.app` URL.

## Option 3: GitHub Pages (Best if using Git)

1.  Initialize a git repository: `git init`.
2.  Commit your files: `git add . && git commit -m "Initial commit"`.
3.  Create a new repository on GitHub.
4.  Push your code to GitHub.
5.  Go to Repository Settings -> Pages.
6.  Select the `main` branch and save.
