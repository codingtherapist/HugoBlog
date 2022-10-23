---
title: "Check Out the MVP for My Stretch Break App!"
date: 2022-10-22T11:38:15-04:00
lastmod: 2022-10-22T11:38:15-04:00
draft: false
author: "Africa Kenyah"
authorLink: "https://www.africakenyah.com"
description: "Your Stretch Breeak has a frontend you can use! Check out the stretch break app."
images: ["featured-image.png"]
resources:
- name: "featured-image"
  src: "featured-image.png"

tags: ["yoga", "MVP", "stretch break", "healthtech"]
categories: ["yoga for developers", "occupational therapy", "web dev", "learning how to code"]

hiddenFromHomePage: false

toc:
  enable: false
---
<h1> Your Stretch Break</h1>
I am so excited to share that my labor of love Your Stretch Break finally has an MVP (minimal viable product)! I like to call in Minimal Lovable Product, which is also the most lovable. This full stack web app has over 50 stretches for you to try on your next computer break for your eyes, neck, shoulders, and hands!
<h2> A Brief Overview</h2>

This project was a dream of mine, over two years in the making. As a virtual occupational therapist and yoga teacher I wanted something for my patients to be able to use that could help them complete exercises as home exercise programs. As I spent more time working remotely via my laptop, I realized I also wanted something for myself and other remote workers to remind us to take a stretch break while working!

Exactly a year ago I decided officially that I was going to learn how to code and make this application a reality. It lived over many iterations and versions and has grown into what you see today.<br>

Check out the project here: https://www.yourstretchbreak.com
![display of homepage of my stretch app application showing a woman stretching on laptop view with caption "Take a 5 minute stretch break", 5 minute timer, and buttons for body parts neck, shoulders, hands, eyes](https://res.cloudinary.com/dtamwfybo/image/upload/v1666532301/Screen_Shot_2022-10-16_at_9.44.29_AM_qviudy.png)<br><br>

![display of homepage in mobile view with html vscode open next to it](https://res.cloudinary.com/dtamwfybo/image/upload/v1665518880/Untitled_design_3_qrni9s.gif)
<br><br>
Be mindful that this is in beta and you may incur a few bugs. This is not the final version but it's ready for you to use on your next stretch break!

<h2> Under the Hood </h2>
This full-stack web application is for tech professionals who work at a computer all day. It allows users to set a 5-minute timer for a stretch break at the top of each hour. Users can click on which body part they would like to focus on during their break, which will display a gif from an array of images randomly on click.

### How It's Made:
Tech used: HTML, CSS, JavaScript, Nodejs, Express, MongoDB

- HTML was used to create the skeleton of the webpage and add information, including alt text to images and buttons.
- Vanilla CSS was used to construct the style of the page, given a very simple format.

Javascript was used to add in functions for page elements including:

- Displaying a random gif from an array of images on click
- Starting a 5-minute countdown timer
- Stopping a timer once timer hit 0 seconds
- Resetting a timer while counting down from a set amount of seconds

NodeJS was used for all backend routes
-Create, Read, Update and Delete functions were created with information being sent to and pulled from MongoDB.


![display of homepage in mobile view with html vscode open next to it](https://res.cloudinary.com/dtamwfybo/image/upload/v1665518366/wire1_cmlcju.png)

![display of homepage in mobile view with html vscode open next to it](https://res.cloudinary.com/dtamwfybo/image/upload/v1665518366/wire2_swux3k.png)


### Optimizations To be added:
- Backend functions including bringing timer and stretch function serverside
- Creating a database of images and gifs that include yoga poses categorized by body part to increase speed and efficiency
- Adding ability to add stretches to database for other users to try
- Adding a social feed
- Creating ability to upload comments without needing to upload photo
- Adding React
- Updating HTML for accessibility
- Simplifying functions for more efficiency


<h2>Final Word</h2>

This project is by no means finished as it needs work to make it ready for mass public consumption. However, I am very proud of how far it's gotten and I hope you enjoy what it has to offer. Please feel free to give me any feedback or advice, I appreciate it! :)