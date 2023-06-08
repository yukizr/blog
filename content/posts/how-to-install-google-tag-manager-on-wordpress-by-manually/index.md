---
title: "How to Install Google Tag Manager on WordPress by Manually"
date: "2022-12-04"
toc: true
categories: 
  - "web"
tags: 
  - "google-tag-manager"
  - "gtm"
  - "install-google-tag-manager-on-wordpress"
  - "wordpress"
---

This is my maiden article in English. Writing a simple tutorial on a popular topic is my way that hopefully to get broad viewers further. I want to give a simple tutorial about how to install Google Tag Manager on WordPress by editing themes directly. This tutorial is suitable for you if your themes don’t have any features to add any extra tracking. This usually happens with free WordPress themes.

## Open your Google Tag Manager Account

![Google Tag Manager workspace](images/GTM-dashboard.jpg)

## Click your container ID on the top right of the window (formatted GTM-XXXXXXX)

![Google Tag Manager container ID](images/GTM-Container-ID.jpg)

## Make sure the code is present on all your page

Put the first code block after opening `<head>` tag. While putting the second code block after opening `<body>` tag.

![Google Tag Manager snippet code](images/GTM-code-block.jpg)

## Open your WordPress then go to the menu Appearance > Editor > header.php

![Install Google Tag Manager on WordPress manually via header.php](images/Install-GTM-on-WordPress-Manually.jpg)

1. Put the first code block after `<head>` tag
2. The second code block after `<body>` tag
3.  Click Update file once everything is okay

## Verify

My tutorial offers two options:

1. [Installing Google Tag Manager extensions (if you Chrome user)](#install_extensions)
2. [See the code present through inspect element on your browser](#inspect_manually)

## Install Google Tag Manager extensions

1. Open the Chrome web store and [install extensions Tag Assistant Legacy (by Google)](https://chrome.google.com/webstore/detail/tag-assistant-legacy-by-g/kejbdjndbnbjgmefkgdddjlbokphdefk)
2. Open your blog > Click the extension > Click enable > Refresh the page > Done

![Google Tag Assistan legacy](images/Google-Tag-Assistant-Legacy.jpg)

## Inspect Manually via Browser Console

1\. On your browser press F12 or click right “Inspect”

![Inspect element on Chrome browser](images/Inspect-Element.jpg)

2\. Go to Elements tab > Ctrl + F

3\. Look up “GTM-”, it will have 3 results. Congrats, you’ve been installed properly!

![Inspecting GTM code on Chrome browser](images/Look-up-GTM.jpg)
