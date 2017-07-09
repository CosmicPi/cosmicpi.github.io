# Cosmic Pi website
CosmicPi, a low-cost, pocket size cosmic rays detector for all Universe enthusiasts. Follow here our progress to make it soon available via crowdfunding.

## Getting started

### Add a new article
To add a new article go to:
https://github.com/CosmicPi/cosmicpi.github.io/new/master/_posts

**Filename** for the new article should be in a format `yyyy-mm-dd-your-title.html` (eg. `2015-04-15-the-birth-of-cosmic-pi.html`) and **Post Template**:  
```
layout: post
status: publish
published: true
title: Your Title
author:
  display_name: James Devine
  email: devine.jd@gmail.com
---
Your content goes here
```


### Upload a file
All files should be stored in `/uploads` directory. To upload a file go to: 
https://github.com/CosmicPi/cosmicpi.github.io/upload/master/uploads

Uploaded file be available at: `https://cosmicpi.github.io/uploads/[file_name.sth]`

### Add a new image
Upload image to `/upoads` directory and then use a template below to insert an 
image to your article:
```html
<div class="image">
    <a href="/uploads/[image_name.jpg]">
        <img src="/uploads/[image_name.jpg]" alt="Image_Title" />
    </a>
    <p>[Image_Title]</p>
</div>
```

### Embed YouTube video
Use a template below to embed a YouTube video to article:
```html
<div class="video">
  <iframe src="https://www.youtube.com/embed/[video_id]" frameborder="0" allowfullscreen></iframe>
  [Video_Title]
</div>
```