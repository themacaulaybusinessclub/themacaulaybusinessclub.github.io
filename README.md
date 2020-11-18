# The Macaulay Business Club Site


## Our Implementation

We hand over a lot of the backend dirty work to Github Pages. Github Pages has built in continuous development. All modified Jekyll files are immediately built by Github and hosted for us. We also use Netlify as a CMS to handle posts and updates. Our solution is a little hacky, but it works and is free. Esseentially, there is a dummy copy of this site hosted at mbcsite.netlify.com. /admin here updates that site which is then copied over to the main repository. The credentials are linked through Github so as long as one has the Github account username and password, everything can be accessed and maintained.

Authorship works as follows. To edit and add posts, one needs to be a contributor on the repository. So, in the future, when we want to allow people to add posts to the blog, we need to first add their github account or allow them to sign in with the master (not recommended). Once they are given access, they can then login at /admin and create/edit posts.

### TODO:

We need to finish configuring the boilerplate. 
1. We should edit the .yml files to reflect the layout and info that we want.
2. We need to update the html templates in `_layouts/` to our liking.
3. We need to add a custom domain in the repository settings and point DNS records to Github pages [documentation](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain). 

In the future, we should probably add the following:
1. A way to manage authorship (as Sanford mentioned). There is probably a way to do this already in Jekyll, but we should research to find a neat solution.
2. A way to edit the master layout pages in the Netlify CMS. Ditto from above. Probably by adding a new "collection" object and adding markdown.

## WhatATheme
**WhatATheme** is a customizable Jekyll Portfolio theme which supports blogging. You can use this theme in order to create an elegant, fully responsive portfolio.

#### You can checkout the [**Demo Here**](https://thedevslot.github.io/WhatATheme/) :boom:

![WhatATheme](assets/images/meta.jpg)

# Features :sparkles:
* Free and Easy setup
* No Coding Required
* Compatible with [Github Pages](https://pages.github.com/)
* Responsive and Blogging Ready
* HTML Compressor using [Jekyll Compress HTML](https://jch.penibelst.de/)
* Minified CSS using SaSS
* CMS Admin Support using [Jekyll Admin](https://jekyll.github.io/jekyll-admin/)
* Supports Latest [Jekyll 4.x](https://jekyllrb.com/) and [Bundler](https://bundler.io/)
* Stylesheet built using SaSS
* Comments using Disqus
* Analytics using Google Analytics
* Instant Search using [Simple Jekyll Search](https://github.com/christian-fei/Simple-Jekyll-Search/)


[<img src="https://i.imgur.com/TVI946Z.png" width="250" />](https://youtu.be/VfPa2c9kwhQ)

---

### Content Credits :green_heart:
* [Hero Image](https://images.pexels.com/photos/220444/pexels-photo-220444.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940) used as a background image in the very first section of Homepage.
* [Author Image](https://cdn.pixabay.com/photo/2015/10/05/22/37/blank-profile-picture-973460_960_720.png) used in the Author Section.
* [Font Awesome](https://fontawesome.com/)
* [Poppins Font](https://fonts.google.com/specimen/Poppins)
* [Memphis Pattern](https://www.freepik.com/free-vector/memphis-pattern-background_4034913.htm#page=1&query=memphis%20pattern&position=23) used for some Social Media Images and the Favicon.

---

### Credits :bulb:
* [Sneha Omer](http://sassyecoder.github.io/)
* [Harsh Trivedi](http://harsh98trivedi.github.io/)

