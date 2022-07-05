- How to render the book? 
  - 1. Render locally with `bookdown::render_book("index.Rmd")`
  - 2. Use `browseURL("docs/index.html")` to review the book locally (or just open `index.html` in a browser)
  - 3. commit and push all changed files to GitHub
        ```
        git add --all *
        git commit -m "update the book"
        git push origin master
        ```