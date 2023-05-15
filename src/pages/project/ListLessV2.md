---
layout: ../../layouts/project.astro
title: ListLessV2
client: Self
publishDate: 2023-05-10 00:00:00
img: /assets/listlessv2.png
description: |
  A web app to help list collectible trading cards faster on eBay.
tags:
  - Vue3
  - Pinia
repoLink: https://github.com/patrickm4/listLessV2
repoName: github.com/patrickm4/listLessV2
---

I happened upon a great collection of Pokemon and YuGiOh cards as well as having a few of my own from my adolescence. My goal was to sell these online and in my early research, eBay was the best place to start. 

<!-- { need screen shots } -->

Version 1 was created with Electron for file system access, but I was always drag and dropping files anyways. So to create features faster, I migrated to a web app with Vue.

<h2>How it works</h2>

The web app takes a file either by drag and drop or browse. For Pokemon files with just the name of the card and its set total (eg. 3/35 number in a card set) I make an API call to a pokemon database to get get more info about the card. If there's no info about the card I display words in buttons that describe the card to append to the name. Also from the API I fetch the the entire catalog of Pokemon sets and display it with their image so I can add that to the name as well 

<!-- {screen shot of full name no btns} -->
<!-- {screen shot of name with btns} -->
<!-- {screen shot of drop down of sets} -->

If its a card other than Pokemon, I don't rely on any API and the file name will have to have the full card title with descriptions.

I also generate an HTML template "description" for ebay listings where I show a simple background, a title and bullet points. I show a textbox so I can easily edit the content in the template.

<!-- {screen shot of description area} -->

<h2>Future goals</h2>

I want to automate the other tedious parts of listing where the info is usually the same like shipping and details of the card.

<!-- View the project here - <a href="https://github.com/patrickm4/listLessV2" target="_blank" class="link">github.com/patrickm4/listLessV2</a> -->
