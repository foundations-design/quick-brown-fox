# 🦊 Quick Brown Fox

## What is it?

From [Wikipedia](https://en.wikipedia.org/wiki/The_quick_brown_fox_jumps_over_the_lazy_dog):

> **"The quick brown fox jumps over the lazy dog"** is an English-language pangram—a sentence that contains all of the letters of the alphabet. It is commonly used for touch-typing practice, testing typewriters and computer keyboards, displaying examples of fonts, and other applications involving text where the use of all letters in the alphabet is desired.
 
It's that, except for HTML

## Quickstart

**1) Clone this repo:**
```bash
git clone https://github.com/foundations-design/quick-brown-fox.git
```

**2) Serve the HTML:**
```bash
cd quick-brown-fox
npx serve
```

Npx copies the URL to your clipboard. Paste it in your browser.

**3) Add Styles:**
Uncomment one of the `<link />` tags in index.html.

## Adding Custom Styles

**Method 1:**

In `index.html`, replace `<link rel="stylesheet" href="index.css" type="text/css" />` with a URL linking to your styles.

**Method 2:**

Replace `index.css` with your custom CSS.

## Overview 

This was built because there isn't a standard HTML file to help make sure a fledgling design system covers all the basic styling needs of a fully-themed web page. 

We believe that at a minimum, it should make this page look okay, **without** the need for any classes.

Currently, this page adds the following inline css for the sake of legibility.

```css
body {
   max-width: 80ch;
   margin: 100px auto;
}
```

You can use this page in any way you find helpful. If you don't know how to link the HTML to your CSS, there's plenty of tutorials on the web. We will consider adding some more guidance here if there's interest.

## HTML Tags

These are the HTML tags that are currently supported:

- `h1`, `h2`, `h3`, `h4`, `h5`, `h6`
- `p`, `strong`(bold), `em`(italic)
- `ul`, `ol`, `li`
- `hr`
- `blockquote > p`
- `pre > code`
- `table`, `thead`, `tr`, `th`, `tbody`
- `form`, `input`, `textarea`, `button` 

There are more tags currently visible on the page, but they may be removed at a later date. It's important we try to keep this lean (but allow options for expansion).

## Looking forward

There's still some decision making to be done on what exactly will be considered basic-level requirements for a theme. There's a good chance it will be somewhat based on the [ComomonMark Spec](https://spec.commonmark.org/). 

Also, it seems that there will be a need second level of requirements for the more ambitious designers. Perhaps these could be based on the [HTML5 Semantic Entities.](https://www.w3schools.com/html/html5_semantic_elements.asp) That's a much more opinionated area, though so it'll be considered at a later date. 





[Some great examples of classless CSS themes](https://github.com/dbohdan/classless-css).

