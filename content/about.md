---
title: About

---

<center>
#### _processing society... <i class="octicon octicon-watch"></i>_
</center>

### Grateful to the amazing work of Yihui Xie https://yihui.name/ !!!

_The aim is to use R based packages and tools for website creation and maintainence_

Main documentation for setup & customization:

* From start to finish https://apreshill.rbind.io/post/up-and-running-with-blogdown/
* Hugo-Xmin Theme Information https://xmin.yihui.name/about/
* Rbind Domain Support https://support.rbind.io/about/

My Customization:

* __Until July 13, 2016__
* Added 'Posts' to menu through `config.toml`
* Removed 'Notes' . Delete `content/notes` directory. [done]
* Removed 'Posts' from appearing in the Home Page. In `layouts/_default/list.html` Add if condition. [done]
* [Enable highlight.js for syntax highlighting of code blocks](https://github.com/yihui/hugo-xmin/pull/5)  `layouts/partials/foot_custom.html` and `layouts/partials/head_custom.html` and `static/css/terms-octicons-hljs-style.css` add `.pre` style
* Added [Categories & Tags](https://github.com/yihui/hugo-xmin/commit/f1e3a90489ec61d903429a582a058b8a1b4d7093) to every post page. In `layouts/_default/single.html` and `static/css/terms-octicons-hljs-style.css` add `.terms` style
* Changed posts layout in `config.toml` to `post = "/post/:slug/"` [done]
* Changed Date Format in `layouts/_defaults/list.html` to `2006, Jan 2` and in  `layouts/_defaults/single.html` to `Jan 2, 2006` [done]
* Added Octicons & FontAwesome CSS to `layouts/partials/head_custom.html` for specific icons e.g. telescope <i class="octicon octicon-telescope"></i> , microscope <i class="octicon octicon-microscope"></i> etc... [done]
* Added CSS code `.mega64-octicon` for 64px icons in `/static/css/terms-octicons-hljs-style.css` add `.megaocticon` and `.mega64octicon` style [done]
* Copied FontAwesome and Octicon fonts and CSS to local directory `static/css` and `static/fonts` instead of CDN. [done]
* Added `favicon.ico` to `static/images/` and link to file `layouts/partial/head_custom.html` [done]