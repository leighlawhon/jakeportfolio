---
layout: posts
title:  "Serenity Editor"
tagline: "A light weight WYSIWYG/markdown editor"
date:   2023-05-01 18:45:59 -0500
tags: [education, finance]
categories: work
highlight_home: true
header:
  overlay_image: "https://images.unsplash.com/photo-1516259762381-22954d7d3ad2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1489&q=80"
  
  caption: "Photo credit: [**Unsplash**](https://unsplash.com/photos/cvBBO4PzWPg)"
---
# Background
I was using Gammerly as a text editor. I wanted a text editor that was web native. A lot of native apps would not support Grammerly. I really wanted to work in markdown. Things like Google Docs are design more for office docs, and does not support markdown. so I would have to translate between formatted text and markdown.

# Approach
I editiing framework called, [TipTap](https://tiptap.dev/), that provided the basic componets to ... I built of this with my own formats. I cuilt the forntend with Svelt. then to be able o use it as a desktop app. I packaged in a way so that it was a progressive web app. Because the app is still being run through your browser, you ca still install extensions and you can use it on the web and it's the same experience, but if you want it to be it's own app you can use it as a progressive web app.

# Results
I was able to create a markdown text editor and it functions well, but I wasn't able to reach the goal and level of flexibility that I wanted. The components my goal was to try and create a more flexible editor that would allow any sort of website to use their own components. They could be anything. It's very hard to provide a true editor with security because you are running untrusted code. There are people using it but I don't have a enough users because I stopped working on it.

# Next Steps
If I return to this project I would start from scratch, taking the lessons I've learned from my first two itterations. I might try and create a new editor that is architected to truely fix the issue