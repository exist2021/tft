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
lastMod: 2023-05-04
---
Now I am so kicked that my blogging woes are finally over. I can straight away publish my linked notes from logseq to my static [Hugo](https://gohugo.io) blog. Yes, this blog is published via schrodinger plugin for logseq. It is developed by young 17 year developer called [Aryan Sawhney]({{< ref "Aryan Sawhney" >}}).

![Schrodinger logseq](https://mataroa.blog/images/961c3445.png)

I have been mostly interacting with Aryan so far, and he has this short way of communicating which is rather difficult to understand but he has patiently taken care of all my issues and now I have a wiki links, backlinks enabled blog.

## How to do it?
Well, go and download the schrodinger plugin on your Logseq desktop app.

> Note - You need to have the developer mode enabled in logseq for this.

Once done, export your logseq graph for Hugo and push the export in to your local GitHub repo where you will be hosting this blog. Now your Github repository is now ready to be turned into a Hugo Blog. ((Check image below)

![Screenshot 2022-08-24 at 5-40-47 PM](https://mataroa.blog/images/82dae657.png)

> There are more detailed instructions on the [GitHub Plugin Page](https://github.com/sawhney17/logseq-hugo-template) if you want to know exact step by step guide.

## Building a Hugo Site via Netlify

Go to [Netlify](https://app.netlify.com), choose import and existing project, connect your GIthub repo.

> Now deploy the Hugo site

### Ok. Three things to remember. Enter the following values. 
1. The command to build - is - hugo
2. Select the base directory
3. Publish directory is - public

## Drawbacks

This ofcourse is a static website which means you need to keep manually pushing updates. Read more on [[Static Vs Dynamic Websites]]

![Screenshot 2022-08-22 at 9-18-42 PM](https://mataroa.blog/images/58ce4b30.png)



> Again a BIG THANKS TO [ARYAN SAWHNEY](https://aryansawhney.com/) for helping me set this blog up via logseq publishing.

## Pending Issues

  + You may want to read this [Issues with schrodinger plugin]({{< ref "Issues with schrodinger plugin" >}})

## Our Monthly Newsletter

  + If you liked this post, do subscribe to  [A monthly roundup of all PKM news | Revue](https://www.getrevue.co/profile/pkmone).
