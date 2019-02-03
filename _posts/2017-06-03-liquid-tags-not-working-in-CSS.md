---
layout: post
title: Liquid tags not working in CSS
postHero: /images/large/slide1.jpg
postAuthor: Amy
authorTwitter: https://twitter.com/amyb008
gravatar: https://1.gravatar.com/avatar/d44fe63cf420551f2b70463077b14f06
---

After discovery of how to impliment liquid tags into my code to use awesome-ness such as a site baseurl and other features, I knew I needed to update my code. I discovered a problem when it came to doing so in my css file. For some reason, my CSS file is rendering the exact tag instead of translating the code. Since making the code robust and more difficult to break is my priority, I chose to use the tags in the html file....for now. 

My current theory is that I need to research file extensions to see if there is a way to instruct the browser to look for a liquid tag syntax. I saw this pattern when I was learning the <a href="https://www.railstutorial.org/book" target="_blank">Ruby on Rails Tutorial</a> using .html.erb, which communicates to the computer that there is embeded Ruby in the file documents. 