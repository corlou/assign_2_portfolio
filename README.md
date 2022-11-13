# A link (URL) to my published portfolio website

Here is a link to [my live portfolio](https://corina.life/)

# A link to my GitHub repo

Here is a link to [my GitHub](https://github.com/corlou)

# Presentation Video

# Description of my Portfolio Website

### Description:

For my portfolio website, I started with a hero-pattern. The leaf background was simple, clean, and elegant which lead me to choosing a dark green for the main colour. I then picked orange for the tertiary colour because while red is opposite green on the colour wheel; it felt to "Christmassy". Finally, I picked a warm white as the secondary colour as it's easier on the eyes.

### Purpose:

The purpose of my website is to showcase my abilities as a software developer. Rather than just hand out a CV with my skills listed, I can also demonstrate them in practise. I was also able to use my knowledge base while also picking up a few new things along the way.

### Functionality/Features:

I think I had the most fun with the CSS animation on my [About Me](https://corina.life/pages/about_me) page. When a user hovers the mouse over the image, it scrolls up to reveal the text. As there was no hover on mobile and for the sake of cleanliness, I removed the animation and just had the images.

The FlexBox that included HTML Semantics Aside and Article was also new to me. It came in handy with the blog posts and I very much enjoyed experimenting with it.

The top navigation menu and the hamburger menu for mobile were a little tricky but time and patience paid off.

### Sitemap

All pages lead to each other but this stiemap shows the parent page and it's children and grandchildren.
![Sitemap that shows connections between pages](/README/sitemap.png)

### Screenshots

Some screenshots of Desktop and Mobile on my live site:
![homepage](/home.png)
![blog homepage](/screenshots/blog_home.png)
![blog post](/README/screenshots/blog_post.png)
![projects page](/README/screenshots/projects.png)
![education page with hamburger](/README/screenshots/education_hambuger.png)
![homepage on mobile](/README/screenshots/home_mobile.png)
![projects page on mobile](/README/screenshots/projects_mobile.png)

### Target Audience

My target audience is potential employers. I want to showcase my skills in action while also refining them.

### Tech Stack

- HTML
- CSS
- JavaScript
- Live Server - to run locally with live reloading upon save
- Netlify

## Other useful Notes and thoughts:

### Understand Flex-Box

- display: flex = Defines a flex container
- flex-direction = which way I want the content to go (left, right, up, down)
- flex-wrap = allows items to wrap onto the next line as needed

### Background vs. Image

In the Projects page, I used a background image for the card container. I will admit that while it feels slighty unconventional to use images in this way, I found it uses less HTML and CSS to achieve the same result. I have demonstrated the ability to use images using the <img> tag in the "About Me" page so this was more of an experiment of what else can be done with images.

### Multiple Stylesheets

Surprisingly, the blog page needed it's own individual styling. So I created a new stylesheet specifically for it. I set a rule that any blog styling needed to have "blog" in front of it to ensure there's no conflict on the main stylesheet. e.g. .blog-card
