# ASA Privacy & Confidentiality Interest Group Website

This repository contains the files that generate our group's official website, which can be found at <https://PrivacyConfidentialityIG.github.io>.

If you're interested in contributing code or resources, we invite you to [become a member of our group](https://PrivacyConfidentialityIG.github.io/join.html) and share your thoughts on [our discussion forum](https://github.com/orgs/PrivacyConfidentialityIG/discussions).

### Instructions for updating this website:

1. Clone the repository and open the .Rproj file, making sure you have quarto installed in your .R environment.
2. Make the changes you want to the .qmd files. Quarto docs: https://quarto.org/docs/guide/
3. Run `quarto render` in Rstudio (button next to `save document`)
     - Note that one render will update all pages that you have edited. (Except `index.qmd` needs to be manually updated -- i.e. if you edit the index page, then you need to hit `render` on the index page, and if you update other pages, you need to hit `render` while not on the `index` page.)
     - It seems safer to run (this should re-render all pages from scratch):
     ```
     library(quarto)
     quarto_render()
     ```
4. Commit and push all changes