# Science Sprint - Grade 10 Physics

A basic interactive South African Grade 10 physics revision game with 13 lessons, 65 questions, worked explanations, XP, hearts, mistake review and a mixed 20-question practice round.

## Publish on GitHub Pages

1. Create a GitHub repository (a public repository is the simplest option).
2. Upload the CONTENTS of this folder to the repository's top level. `index.html` must be at the repository root, not inside another folder. Do not upload the ZIP itself.
3. Commit the uploaded files to the `main` branch.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, set Source to Deploy from a branch.
6. Select the `main` branch and `/(root)` folder, then click Save.
7. Wait for deployment to finish. Settings > Pages will show your site link.

For a normal project repository, the address is https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/.

## Files

- `index.html`: the complete app, including its styles, questions and JavaScript.
- `.nojekyll`: an empty file that bypasses Jekyll processing. If your file picker hides it, the app still works with just index.html.
- `README.md`: these instructions.

No installation, build command, dependencies, API keys or server is required. You can also open index.html directly in a browser.

Progress is stored in the current browser's local storage. It does not sync between devices or browsers. Moving from the downloaded file to the hosted website starts a separate progress history.

The exam-practice mode is a 20-question revision round with immediate feedback, rather than a full timed 100-mark examination.

## Validation

JavaScript syntax and game logic were checked, including all 65 correct answers, lesson completion, scoring, mistake review, mixed-round topic coverage and heart refills. Visual browser testing was unavailable.

## GitHub documentation

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
