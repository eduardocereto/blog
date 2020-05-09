---
title: "My First Post"
date: 2020-05-09T05:33:54-07:00
draft: false
---

Testing my hugo blog!

Took me hours to set it up the way I wanted. That list contained:

 - Choosing a theme. Settled for [this one](https://themes.gohugo.io/hugo-coder/)
 - Setting up VSCode with some Hugo Extensions.
    - [vscode-hugo-snippets](https://github.com/fivethree-team/vscode-hugo-snippets)
    - [language-hugo-vscode](https://github.com/theNewDynamic/language-hugo-vscode)
    - [better-toml](https://github.com/bungcip/better-toml)
 - Setting up a [gitHub Action](https://github.com/eduardocereto/blog/blob/e1c7a5b8cec288f6c382acc24a6b21a67e4bff1c/.github/workflows/ci.yml) to automatically deploy to firebase hosting. Not perfect but it did the job.
 - Setting up Firebase itself to host the blog including with my custom domain
    - Initially tried to setupo with Google Cloud Storage, but it turns out that does not support SSL on custom domains. Quite useless if you ask me. Firebase was thankfully a blessing to use.

Honestly this was an incredible time sink. Maybe I'm not that good or maybe I was context switching too much
but it's easy to think this was not worth the investment. Specially because my previous multiple blogs ended up abandoned
after a week or two. 

But hey, this is a first post. So let's be optimistic. 

There are still a few steps to go though. Listing here for future reference.

 - Configure Disqus for comments
 - Customize Theme
 - Write an About page
 - Figure out what the heck are archetypes
 - <s>Maybe use a service such as https://forestry.io/ as a CMS.</s> - I tried, not for me.

 Lots of topics for future posts :).