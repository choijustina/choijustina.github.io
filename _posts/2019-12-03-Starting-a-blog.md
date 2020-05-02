---
layout: post
title: Starting a blog
date: 2019-12-03
tags: tutorial, blogging
---

After procrastinating on starting a blog for years, I finally decided to use Github Pages. That way, I could use version control I'm already familiar with and Github recommends Jekyll because it is faster and cleaner as a static site hosting service.

I did have to spend some more time familiarizing myself with the specifics of Markdown (my prior knowledge is elementary and I still keep mixing up which brackets to use for links) but this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) includes all of the basics.

I had initially forked the repo as based on this [tutorial](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) (which only took 30 minutes btw), but then I realized I wanted to start with a clean slate. Honestly, I also didn't like how when I forked the repo, there were other contributers/branches/stats. Petty and perfectionist, I know. I do recommend the tutorial though, as it includes other useful tips and optional steps.

## Directions
1. Follow Quickstart instructions from [Jekyll](https://jekyllrb.com/docs/). Easy! There is also a [step-by-step tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/)

1. Rename your repository to *username.github.io* It will now be accessible at *username.github.io* from your web browser.
	+ Note: Your site might not be published yet (it should be after step 3, or after commiting any changes within your repository)

1. Personalize the `_config.yml`

1. Write your first post! Edit `/_posts/2014-3-3-Hello-World.md` and update the date and title of your post. Your website should be rebuilt automatically so that the `READ MORE` link points to your first post.
	+ Note: Jekyll follows the following naming convention: `YEAR-MONTH-DAY-title.md` where `YEAR` is four digits and `MONTH` and `DAY` are both two digits.


Don't repeat my mistake: I didn't install the **full** Ruby development environment as instructed in the [guide](https://jekyllrb.com/docs/installation/#requirements). So when I went to build the site by running `bundle exec jekyll serve`, I got an error `Could not locate Gemfile or .bundle/ directory`

But finally after some Googling and an hour of effort, I finally got it to work! And GitHub SSH keys set up too!

## Next steps: 
+ Learning about Front Matter and Liquid templating [here]({% post_url 2019-12-04-Liquid-Templating-language %})
+ Pro tip: [linking to other posts](https://jekyllrb.com/docs/liquid/tags/#linking-to-posts)

#### Other useful resources:

* <https://help.github.com/en/github/working-with-github-pages/about-github-pages-and-jekyll>
* <https://help.github.com/en/github/working-with-github-pages/getting-started-with-github-pages>
* <https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site>
* <https://help.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site>
* <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>