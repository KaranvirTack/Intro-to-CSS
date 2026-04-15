# Intro-to-CSS
CSS-Methods
In this exercise, you're going to practice adding CSS to an HTML file using all three methods: external CSS, internal CSS, and inline CSS. You should only be using type selectors for this exercise when adding styles via the external and internal methods. You should also use keywords for colors (e.g. "blue") instead of using RGB or HEX values.


Class-ID
For the colors in this exercise, try using a non-keyword value (RGB, HEX, or HSL). The properties you need to add to each element are:
All odd numbered elements: a light red/pink background, and a list of fonts containing Verdana and DejaVu Sans with sans-serif as a fallback
The second element: blue text and a font size of 36px
The third element: in addition to the styles for all odd numbered elements, add a font size of 24px
The fourth element: a light green background, a font size of 24px, and bold

Grouping
Let's build a little off the previous exercise. Here, you're going to give two elements each a unique class name, then add rules for styles that both elements share as well as their own unique styles.The properties you need to add to each element are:
The first element: a black background and white text
The second element: a yellow background
Both elements: a font size of 28px and a list of fonts containing Helvetica and Times New Roman, with sans-serif as a fallback

Chaining
We have two images for you to style, each with two class names, where one of the class names is shared. The goal here is to chain the selectors for both elements, so that each have a unique style applied, despite using a shared class selector.
The properties you need to add to each element are:
Make the element with both the avatar and proportioned classes 300 pixels wide. We want it to automatically retain its original square proportions, so don't hardcode in a pixel value for its height.
Make the element with both the avatar and distorted classes 200 pixels wide, then make its height twice as big as its width (here you should hardcode in a pixel value).

Descendant
The goal of this exercise is to apply styles to elements that are descendants of another element, while leaving elements that aren't descendants of that element unstyled.
The properties you need to add are:
Only the p elements that are descendants of the div element should have a yellow background, red text, a font size of 20px, and center aligned.
