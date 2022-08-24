---
date: 2022-08-13 23:40
category:
- logseq
tags:
- Aryan Sawhney
- Schrodinger
title: How to publish your logseq notes to a Hugo with Schrodinger Plugin
categories:
- logseq
lastMod: 2022-08-24
---
Now I am so kicked that my blogging woes are finally over. I can straight away publish my linked notes from logseq to my static [Hugo](https://gohugo.io) blog. Yes, this blog is published via schrodinger plugin for logseq. It is developed by young 17 year developer called [Aryan Sawhney]({{< ref "Aryan Sawhney" >}}).

![Schrodinger logseq](https://mataroa.blog/images/961c3445.png)

I have been mostly interacting with Aryan so far, and he has this short way of communicating which is rather difficult to understand but he has patiently taken care of all my issues and now I have a wiki links, backlinks enabled blog.

## How to do it?
Well, go and download the schrodinger plugin. I think you need to have the developer mode enabled in logseq for this. Once done, export your logseq graph for hugo and push the folders in to your local GitHub folders and voila your blog is ready. There are more detailed instructions on the [GitHub Plugin Page](https://github.com/sawhney17/logseq-hugo-template) if you want to know exact step by step guide.

## Building a Hugo Site via Netlify

Go to Netlify, choose import and existing project, connect your GIthub repo.

> Now deploy the Hugo site

### Ok. Three things to remember. Enter the following values. 
1. The command to build - is - hugo
2. Select the base directory
3. Publish directory is - public
![Screenshot 2022-08-22 at 9-18-42 PM](https://mataroa.blog/images/58ce4b30.png)

## Static Vs Dynamic website
The only issue with static websites is you need to export your graph all the time even when you update one word correction and then push the same to your github folder and then let the site build itself. I am using [netifly](https://app.netlify.com/) to publish my hugo site. 
But since GitHub is free and Netifly is also free, and Hugo looks gorgeous so I don't really mind this mild inconvenience.

> Again a BIG THANKS TO [ARYAN SAWHNEY](https://aryansawhney.com/) for helping me set this blog up via logseq publishing.

## Pending Issues

  + You may want to read this [Issues with schrodinger plugin]({{< ref "Issues with schrodinger plugin" >}})

## Our Monthly Newsletter

  + If you liked this post, do subscribe to  [A monthly roundup of all PKM news | Revue](https://www.getrevue.co/profile/pkmone).