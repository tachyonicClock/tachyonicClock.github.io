+++
title = 'Native Ish Theme'
date = 2025-10-12T13:26:38+13:00
draft = true
+++

Form follows function is the idea in design that the appearance of something is dictated by its purpose[^1]. This is utilitarian design. 

Assuming the function of something does not change neither will its form. Fashion changes but function is a constant.  


## Line Width

How long should a line of text be? Characters per line (CPL) measure the length of a line. If the line is too short, the reader's eye frequently travels back and forth to find the next line. This can be disruptive and make the text more disjointed. If the lines are too long, the distance the eye must travel makes it challenging to find the next line.

Following our ethos of "form follows function," what is the best line length? The answer depends on what our goal is. To summarize the Wikipedia page on the matter[^2]:

* 34-60 CPL, 45 is optimal, for novice readers.
* 45-80 CPL, 60 is optimal, for expert readers.
* Longer lines are better for scanning.
* Shorter lines are better for accuracy.

I picked 60 CPL for this site:
```css
p {
    max-width: 60ch;
}
```

**What about code?** 80 CPL is the traditional and a common CPL for code. This presents a problem because the body text is 60 CPL. You could simply have an overhang of 20 CPL for code blocks, but this is odd on mobile devices where the whole screen should be used.


## Colours

This theme uses system colours to match the user's operating system theme. This is done using CSS system-colours[^3]. The idea is that the user has already picked a colour scheme they like and are comfortable reading.

```css
:root {
  color-scheme: light dark;
}

body {
    background-color: Canvas;
    color: CanvasText;
}

a {
    color: LinkText;
}
a:visited {
    color: VisitedText;
}
```

[^1]: https://en.wikipedia.org/wiki/Form_follows_function
[^2]: https://en.wikipedia.org/wiki/Line_length
[^3]: https://developer.mozilla.org/en-US/docs/Web/CSS/system-color



