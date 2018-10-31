# githubpages-template

This is a template for a basic GitHub Pages website produced with RMarkdown. Follow these instructions:

1. Fork this repository (top right). 
2. Rename it.
3. Ensure GitHub Pages is enabled in settings and set this to master branch. Here you will find the URL of your website.
4. Go back to your repo and click on Clone or Download (top right). Choose SSH (not HTTPS), and copy the remote URL. 
5. Start a new project in RStudio and choose Version Control -> Git. Here, paste the remote URL under Repository URL. Name your project as usual and create project. This clones the forked repo ready to use.
6. Change your website name and title in _site.yml.
7. Build the site in RStudio (rmarkdown::render_site()).
8. Commit changes (git commit -a) and push them to GitHub (git push origin master).
9. Open your website at the URL in settings. 
10. Hope for the best. 
