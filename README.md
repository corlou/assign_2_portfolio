# Understand Flex-Box

- display: flex = Defines a flex container
- flex-direction = which way I want the content to go (left, right, up, down)
- flex-wrap = allows items to wrap onto the next line as needed

# Background vs. Image

In the Projects page, I used a background image for the card container. I will admit that while it feels slighty unconventional to use images in this way, I found it uses less HTML and CSS to achieve the same result. I have demonstrated the ability to use images using the <img> tag in the "About Me" page so this was more of an experiment of what else can be done with images.

# Multiple Stylesheets

Surprisingly, the blog page needed it's own individual styling. So I created a new stylesheet specifically for it. I set a rule that any blog styling needed to have "blog" in front of it to ensure there's no conflict on the main stylesheet. e.g. .blog-card
