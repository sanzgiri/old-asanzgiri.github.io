---
layout: page
title: About
permalink: /about/
---

How this blog is set up:

* Source Code is at <https://github.com/sanzgiri/asanzgiri.github.io>. 

* To create a new post, add a file to the `_posts` directory that is named in the format `YYYY-MM-DD-name-of-post.md`. This can be done directly on github. The top of the .md file should be:
<br>
<br>

```
---
title: Name of Post
date: YYYY-MM-DD 00:00:00 Z
permalink: "/name-of-post"
layout: post
excerpt: This post is about...
---
```

* Alternately, you can clone this repo and edit and serve from your linux/mac system:
```
git clone https://github.com/sanzgiri/asanzgiri.github.io
cd asanzgiri.github.io
edit YYYY-MM-DD-name-of-post.md
### Test locally using "jekyll serve" and viewing blog locally on "http://127.0.0.1:4000/"
git add YYYY-MM-DD-name-of-post.md
git commit -m "comment" YYYY-MM-DD-name-of-post.md
git push origin master
```

* Blog settings are in the `_config.yml` file.

* I use netlify to serve the blog from github. Netlify has been configured to use the custom domain `hoopedondata.com`.

---
<br>
<br>
This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
