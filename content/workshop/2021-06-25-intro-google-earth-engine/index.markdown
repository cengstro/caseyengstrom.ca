---
title: Intro to Google Earth Engine Workshop Homepage
author: Casey Engstrom
date: '2021-06-25'
slug: intro-google-earth-engine
categories: []
tags: [google-earth-engine, javascript, remote-sensing, workshops]
subtitle: ''
summary: 'Workshop materials for participants.'
description: ''
authors: []
lastmod: '2021-06-25T16:58:32-07:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

Welcome to the homepage for Google Earth Engine 101 workshop. 

- [Syllabus](#syllabus)
- [Pre-requisites](#pre-req)
- [Slides](https://docs.google.com/presentation/d/156572dqZvHS-58NtxL7zy0mAW6FZNdfOhZmV2z8rkoQ/edit?usp=sharing&resourcekey=0-N1RJmtJfHqFXoA0Q56YjWg)
- [Code repository](https://code.earthengine.google.com/?accept_repo=users/caseyengstrom/GEE101)


## Syllabus {#syllabus}

The workshop is split into 12 lessons, and takes place over three 2-hour sessions.

#### Day 1
- GEE overview [presentation](https://docs.google.com/presentation/d/156572dqZvHS-58NtxL7zy0mAW6FZNdfOhZmV2z8rkoQ/edit?usp=sharing&resourcekey=0-N1RJmtJfHqFXoA0Q56YjWg)
- 1 Client vs Server
- 2 Hello, Images
- 3 Computations on Images
- 4 Spatial reductions

#### Day 2
- 5 Image collections
- 6 Vectors
- 7 Functions
- 8 Mapping functions
- 9 Reducing Collections

#### Day 3
- 10 Cloudmasks
- 11 Charts
- 12 Exporting data
- Wrap up

The workshop is intended to get you comfortable with coding in the Code Editor, as such all course materials are available in the [GEE101 repository](https://code.earthengine.google.com/?accept_repo=users/caseyengstrom/GEE101). 

Each lesson is divided into three parts: Demo, Problem, and Solution. We'll spend a few minutes going over some demo code together to introduce concepts, and then cut you loose to try tackling a problem in the Problem script. The Problems are pretty similar to the Demo, but give you a chance to try it for yourself. After the majority of the class has indicated they are ready to move on, we can review the Solution and talk through any questions.



## Pre-requisites {#pre-req}

##### 1. [Sign up for a Google Earth Engine account](signup.earthengine.google.com) at least one week before the workshop

Sign in with your Google credentials, and complete the application. It may take several days for your application to go through. 

![gee-signup](gee-signup.png)

##### 2. Check your application status

Visit the [Code Editor](https://code.earthengine.google.com/?accept_repo=users/caseyengstrom/GEE101). If your application was successful, you should see something like this, with your profile icon in top right.

![code-editor](code-editor.png)

If your application was unsucessful, you might see something like this:

![application-denied](application-denied.png)

If you have followed the instructions on the error page, and are still not able to log in, please [contact](mailto:s_zhang@sfu.ca) the workshop instructors.


##### 3. Get to know Google Git

Git is like Microsoft Word's 'track changes' for coders. In the Scripts panel on the left side, click “Reader”, and click to open the GEE101 repository “users/caseyengstrom/GEE101”. As a Reader, you can view my scripts, but cannot make changes to my original script. Try altering the script by typing a few characters, and click 'Save'---a prompt will remind you that this file is read-only, and ask if you would like to make a copy of it. Another prompt will ask you to create a new repository, and then will save your version of the script to it.  

![save1](save1.png)
![save2](save2.png)

##### 4. Complete the Javascript Basics lesson in the Code Editor.

Don't worry, you only need to know very rudimentary basics for GEE. Variables start with 'var', know what a list and a dictionary are, and understand how to write a simple function and you're be fine. Read through the Demo, follow the commented instructions to run the script. Then test your knowledge by working through the problem set. 


## Credit

These materials are based on teaching material developed by Nick Clinton, Google Earth Engine Developer Relations, and modified by myself. Hosted by [Simon Fraser University Library Research Commons](https://www.lib.sfu.ca/about/branches-depts/rc) in [March](https://www.lib.sfu.ca/find/other-materials/data-gis/gis/36086) and [July](https://www.lib.sfu.ca/find/other-materials/data-gis/gis/satellite-image-analysis-google-earth-engine-online) 2021.
