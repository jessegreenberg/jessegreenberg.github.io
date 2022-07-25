To start jekyll server run `bundle exec jekyll serve`.
More information at https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll.

To put a build of titan in this, build the titan project with npx react commands. THen change the hrefs in the
build index.html to point to the relative location so jekyll knows where they are. For example
```href="/static/css/main.31d6cfe0.css"``` to
```href="./static/css/main.31d6cfe0.css"```




