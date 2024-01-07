# auto_landing_page

1. Write down the goal of the landing page, including two paragraphs that explain what the product does and how it works.
2. Insert images from `example` folder into chatgpt while using `You are a professional web designer helping to design a landing page for my website.` as system prompt and the following prompt, replacing "description" with the description from step one:


```prompt
I have an open-source project that I now want to convert into a SaaS. For this purpose, I am building a website. Following the description of the software: 

---
description
---

on the images you can see a website template, please provide me with appropriate text for the website but adjusted to my SaaS idea.
```
3. Insert content into the webpage, but make adjustments to the content if necessary.
4. Add the logo to the `public/image/logo.png` directory, and then go to `components/ui/logo.tsx` and change the name of the landing page.
5. Generate a Figma or Excali Draw design that visually explains what the application does. Save this diagram to the image folder and, if necessary, adjust the height of the container in ﻿hero.tsx to avoid taking up too much whitespace.
6. Change the tab metadata appropriate to your product. Prompt ChatGPT for this.
7. Changing the text from ChatGPT in the whole landing page can be tedious, but use `command + shift + f` inside of VSC for string matching where you have to place the new text.
8. Create a new property in Google Analytics and insert the Google Analytics code on the page.
