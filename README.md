This blog is built with [blogdown](https://github.com/rstudio/blogdown) and [Hugo](https://gohugo.io/), with the [Academic](https://sourcethemes.com/academic/) theme. I deploy my blog using [Netlify](https://www.netlify.com/). This blog was forked from [Julia Silge](https://juliasilge.com/).

My blog posts are released under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

This blog is more or less structured as per blogdown default. A few pointers (mostly a reminder for myself): 
- config/
  - menus.toml controls site menu
  - params.toml controls background image
- content/
  - authors/admin/_index.md contains my bio page
  - blog/ contains the blog .md files
  - home/ contains the website home page
  - workshop/ contains my workshop .md pages
- public/ contains the public-facing website. Directory contents automatically updated after running blogdown::build_site() 
- static/ should contain things like images, pdfs, etc
