# Showcase Lite
A lightweight, single-file template for creating offline viewable slides, with no external dependencies.

# Why?
- No time to fiddle, need slides quick.
- We may have a Mac. Or linux. Or windows. Not sure.
- We may be underground, and there's no wired network either.
- Screen resolution might be unexpected.
- Single file makes it difficult to misuse
- Browser works.

# How?
- Edit the file and reload. There's no building step.
    - To add a slide, add a div with the "slide" class inside the div with id="main".
    - The slideshow will start at the slide marked with the class "current".
    - You may add a transition class to the slide div:
        - enter-left
        - enter-right
        - enter-up
        - enter-down
        - enter-fade
        - enter-vflip
        - enter-hflip
    - Inside the slide, you may add a div using a content type class for standard slide layouts:
        - type-cover: contains divs with classes "title" and "subtitle".
        - type-title: contains divs with classes "title" and "body" (or "left-body, right-body" for split content) and "footer-right".
    - You may add custom styles if you need them.
    - You may add javascript if you need it.
    - You may add references to external files if you really want to.
    - If you need images and want to keep the single file, you can use data URIs or svg.
