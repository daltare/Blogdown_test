This is built with the R package `blogdown`.

This set of files was created using the Rstudio interface and selecting `File -> New Project -> New Directory -> Website Using Blogdown` 

To build the website and load it into a web browser, run `blogdown::serve_site()`

To deploy the website on GitHub pages, the `public/` directory should be the GIT repository. Also, you will need to put a `.nojekyll` file inside the `public/` directory. So, after creating the `.nojekyll` file, initialize the GIT repository in the `public/` directory, then push it to a new GitHub repo, then go to the **Settings** tab for the repository, scroll down to the **GitHub Pages** section, and set the source to **master branch**

More detailed instructions on how to create a blog site with blogdown are available here: https://bookdown.org/yihui/blogdown/
