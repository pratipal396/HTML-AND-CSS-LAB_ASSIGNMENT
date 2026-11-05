Lab 10: CSS Fundamentals


Aim Apply CSS in three ways and use element, class and id selectors.

Theory

CSS (Cascading Style Sheets) controls how HTML looks.
Three ways to add CSS: inline (style="..." on a tag), internal (<style> in the head) and external (a .css file linked with ). External is best because one file can style many pages.
Selectors: element (h1), class (.note) and id (#title).
Specificity: id beats class, class beats element. Inline style beats all of them. If two rules have equal weight, the later one wins (the cascade).
Files in this folder

inline-internal.html: Inline style on one paragraph and internal style for h1 and .highlight.
style.css: External stylesheet with element, class and id rules.
linked.html: Page linked to style.css.
How to check Open with Live Server and screenshot the pages.