---
draft: true
date: 2020-05-09T13:09:10-07:00
title: "Hugo Begginer Tips"
description: ""
slug: "" 
tags: []
categories: []
externalLink: ""
series: []
---

You have finished your Hugo configuration. And most importantly it's deployied using an automated CI/CD pipeline after you push it into your gitHub repo. Now what? Here are some essential things you need to know to become a pro. 

## Use archetypes

here's one I store under `archetypes/posts.md`.

{{< highlight markdown >}}
---
draft: true
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}"
description: ""
slug: "" 
tags: []
categories: []
externalLink: ""
series: []
---
{{< /highlight >}}

It contains some basic fields I want to use for all my posts. So I never forget to include them. It also capitalizes the post titles nicely.

## 