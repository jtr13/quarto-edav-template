This repo contains a [Quarto book](https://quarto.org/docs/books/) template for the EDAV final project.

## Follow these instructions carefully

*If you have any difficulties or have feedback of any kind, please [file an issue](https://github.com/jtr13/quarto-edav-template/issues) or ask questions in the [Discussions](https://github.com/jtr13/quarto-edav-template/discussions) section.*

[Video tutorial](https://www.youtube.com/watch?v=emgS2JI4jCk) (walkthrough of steps below)

### Copy this template (GitHub)

- [ ] 1. Click the green "Use this template" button above and choose "Create a new repository". If you don't see the "Use this template" option, **log in to GitHub**. DO NOT FORK THE REPO. Choose a descriptive name for your repo, such as "federalbudget" or "AIDSdeaths". (If you change your topic before you do any work, delete the repo and start over.)

- [ ] 2. Leave the setting for viewing the repo as "Public". (Otherwise, we will not be able to access your rendered book.)

- [ ] 3. In the Description field, write "Source files for final project" then click "Create repository".

### Set up Pages (GitHub)

- [ ] 1. You've now left the template page and are viewing your new repo on GitHub. On the home page, click Settings. Click the "Pages" section on the left. In the Build and Deployment section, set Source to "Deploy from a branch" (Classic Pages experience) and Branch to main with /docs folder. Click Save.

- [ ] 2. Click the little gear button near "About" on the top right side of the home page of the repo and check the "Use your Github Pages website" box under "Website". Click "Save changes". Test the link and you should see a web site with a stick figure on it. It may take a few minutes to build so if it's not working do a few more steps and then come back to check.

### Copy the repo link (GitHub)

- [ ] 1. Click the green Code button, choose "HTTPS" and copy the link below. It should have the format: https&#xfeff;://github.com/[USERNAME]/[REPONAME].git

### Clone the repo (RStudio)

- [ ] 1. Clone your new repo with *File, New Project..., Version Control, Git* in RStudio. You will need to paste the link from the previous step in the Repository URL box. If it's not automatically populated, enter the repo name in the "Project directory name:" box. Choose the location of the project.

### Edit `_quarto.yml` (RStudio)

Tip: From the file pane in RStudio, open `README.md`, which contains these instructions. You can delete steps as you complete them.

- [ ] 1. Change the all caps info in the `title:`, `author:` and `repo-url` fields in the YAML (top) section of `_quarto.yml` to your info. (Note: it's very important to maintain the indenting structure in this file precisely as is -- be careful!)

### Render the book (RStudio)

- [ ] 1. If you haven't already, click "Help" "Check for Updates" to make sure you have the latest version of RStudio (and thus have Quarto installed.)

- [ ] 2. Render the web site locally by clicking the "Build" tap on the right and then "Render Book".

- [ ] 3. Use `browseURL("docs/index.html")` to view your book locally (or just open `docs/index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book on GitHub Pages.)

### Update README (GitHub or RStudio)

- [ ] 1. Delete the content of this **README** and add a short description of your project in its place. If you're working locally, be sure to commit and push the changes to GitHub.

### Optional

- [ ] 1. Choose a theme from [https://bootswatch.com/](https://bootswatch.com/) and replace "cosmo" in `_quarto.yml` with your prefered theme.

### Additional features

Please consult the official guide to **quarto** book websites: [https://quarto.org/docs/books/](https://quarto.org/docs/books/)



