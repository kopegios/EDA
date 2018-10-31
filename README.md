# githubpages-template

This is a template for a basic GitHub Pages website produced with RMarkdown. Follow these instructions:

1. Fork this repository (top right). 
2. Rename it.
3. Ensure GitHub Pages is enabled in settings and set this to master branch. Here you will find the URL of your website.
4. Go back to your repo and click on Clone or Download (top right) with HTTPS. 
5. Start a new project in RStudio and choose Version Control -> Git. Here, paste the remote URL under Repository URL. Name your project as usual and create project. This clones the forked repo ready to use.
6. Change the name and  website title in _site.yml.
7. Build the site in RStudio (rmarkdown::render_site() or cmd/ctrl + shift + B).
8. Commit changes (top right of RStudio, under the Git pane), ticking the files you have changed. 
9. Push the changes (green up arrow in the Git pane). 
10. Go back to your GitHub repository. You should see changes to the files with your recent commits.
11. Open your website at the URL found in your GitHub repository's settings. 
12. Hope for the best (this might take a couple of minutes to build).  
