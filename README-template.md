# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
-google fonts 

### What I learned

I have learned about css flexbox.

To see how you can add code snippets, see below:

```html
<div class="mainContainer">
    <div class="firstContainer">
            <img src="images/image-qr-code.png" alt="QR code">
        <div class="word">
            <h3>Improve your frontend skills by building projects</h3>
            <p>scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>
    </div>
```
```css
.mainContainer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color:hsl(212, 45%, 89%);
    min-width: 100vw;
    min-height: 100vh;
}
.firstContainer {
    display: flex;
    align-items: center;
    flex-direction: column;
    background-color: hsl(0, 0%, 100%);
    max-width: 250px;
    max-height: 600px;
    border-radius: 20px;
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

need to reduce code lines and I should learn more css tips for layouts.

### Useful resources

www.font.google.api.com

## Author

- Website - [QR code component](https://www.your-site.com)
- Frontend Mentor - [DannyTrojan](https://www.frontendmentor.io/profile/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
