# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#Social links profile)
  - [Screenshot](./Frontend%20Mentor%20_%20Social%20links%20profile%20-%20Google%20Chrome%2010_7_2026%202_54_43%20PM.png)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](VS Code)
  - [What I learned](Html & Css)
  - [Continued development](learn how to use css )
  - [Useful resources](https://developer.mozilla.org/en-US/ , https://www.w3schools.com/)
  - [AI Collaboration](Claude Code)
- [Author](kendo)
- [Acknowledgments](Me and Claude)
**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Frontend%20Mentor%20_%20Social%20links%20profile%20-%20Google%20Chrome%2010_7_2026%202_54_43%20PM.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/ILM3211/Social-links-profile)
- Live Site URL: [Add live site URL here](https://ilm3211.github.io/Social-links-profile/)

## My process

### Built with

-VS Code
-HTML 
-CSS

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  
  <title>Frontend Mentor | Social links profile</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 0.6875rem; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
 <link rel="preconnect" href="https://fonts.googleapis.com">
 <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
 <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
  <img src="./assets/images/avatar-jessica.jpeg" alt="Jessica Randall avatar profile">
  <h1 class="weight-7" >Jessica Randall</h1>
  <p class="weight-6">London, United Kingdom</p>
  <p class="Description">"Front-end developer and avid reader."</p>

  <a href="https://github.com/" class="block">GitHub</a>
  <a href="https://www.frontendmentor.io/" class="block">Frontend Mentor</a>
  <a href="https://th.linkedin.com/" class="block">LinkedIn</a>
  <a href="https://x.com/" class="block">Twitter</a>
  <a href="https://www.instagram.com/" class="block">Instagram</a>
</div>
  
  <footer class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge">Frontend Mentor</a>. 
    Coded by <a href="#">Kendo</a>.
  </footer>
</body>
</html>
```
```css
body {
     box-sizing: border-box;
    background-color: hsl(0, 0%, 8%);
    color: hsl(0, 0%, 100%);
    font-family: "Inter", sans-serif;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    padding: 24px;
    font-size: 14px;
}
.container {
    display: inline-block;
    box-sizing: border-box;
    border-radius: 10px;
    width: 100%;
    max-width: 384px;
    align-content: center;
    text-align: center;
    background-color: hsl(0, 0%, 12%);
    padding: 25px;
}
img {
    border-radius: 100%;
    height: 100px;
}
.weight-7 {
    font-size: 1.6rem;
    font-weight: 700;
    margin-bottom: 0;
}
.weight-6 {
    font-weight: 600;
    padding-bottom: 25px;
    color:hsl(75, 94%, 57%);
}
.Description {
    margin-bottom: 25px;
    font-weight: 400;
}
.block {
    display: block;
    text-decoration: none;
    color: white;
    background-color: hsl(0, 0%, 20%);
    width: 100%;
    height: 30px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 15px;
    margin-bottom: 16px;
    border-radius: 10px;
    font-weight: 700;
}
.block:hover , .block:focus {
    background-color:hsl(75, 94%, 57%);
    color: black;
}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/) - This help me about html and css
- [Example resource 2](https://www.w3schools.com/) -This is another website that help me with html and css

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

-i use ai to hint and guide me
-if i not know answer for too long to use a to answer me


**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

## Author

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
