# Template-Slides-Students

This is the template for slide sets made for the student track of the train the trainer program.

# Important notes for publishing the slides via GitHub pages
For collaborative efforts on GitHub, it is necessary for collaborators to directly view the website from GitHub pages. Since the content consists of a singular qmd file instead of multiple files, we need to first force the generation of a local docs folder within our local project, render and push to GitHub (see https://quarto.org/docs/publishing/github-pages.html for more reading). The steps are:
1. Generate a _quarto.yml file within R
2. Add the following to the _quarto.yml file
project:
  type: website
  output-dir: docs
3. Rename qmd file into index.qmd
4. Render locally
5. Stage and commit locally
6. Push to remote repository
7. Set repository to public
