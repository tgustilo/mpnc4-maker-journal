# Unpacking CSS

What are the typical modules in any css code or theme?

Need to unpack the various pieces and decide which are the most important for no-code use, and what no-code tools can be used to generate those modules and then use them / drop them in to projects.

Normalize / reset

Classless css, i.e. basic for all html elements without special classes or ideas; presumably this is what styles all markdown (along with branding and typography effects, see below)

Branding: fonts, colors, image & icon assets, plus maybe:
Header (banner / top bar, nav) and footer. (See TOBY / CSS Suitcase project)

Typography and text effects: how are headers, body paragraphs, bold, italic, highlight, links, etc styled? Also hover, clicked, etc. (See also buttons under components below)

General layout / responsive: includes the page, container, body, all general page set-up, including for different screen and device sizes to make it responsive

Grid / responsive: the rows and columns used to space stuff

Image stuff (maybe also include special js for image processing, sizing, etc)

Components (usually as panels) - all the special css needed for specific drop-in components, whether pricing tables, accordions, forms, buttons, and so on (see also header and footer in branding).

Embeds and frames. What happens when you drop in stuff?

Animations, special effects? Stuff formerly deal with via js

---

Related: html and templating
Related: javascript libraries (much now in css?)

