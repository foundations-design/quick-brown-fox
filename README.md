# 🦊 Quick Brown Fox - An HTML/CSS Previewer

## Quickstart

**1) Clone this repo:**
```bash
git clone https://github.com/foundations-design/quick-brown-fox.git
```

**2) Serve the HTML:**
```bash
cd quick-brown-fox/src
npx serve
```

`npx` copies the URL to your clipboard. Paste it in your browser.

**3) Add Styles:**
Uncomment one of the `<link />` tags in index.html.

---

## Intro

From [Wikipedia](https://en.wikipedia.org/wiki/The_quick_brown_fox_jumps_over_the_lazy_dog):

> **"The quick brown fox jumps over the lazy dog"** is an English-language pangram—a sentence that contains all of the letters of the alphabet. It is commonly used for touch-typing practice, testing typewriters and computer keyboards, displaying examples of fonts, and other applications involving text where the use of all letters in the alphabet is desired.
 
It's that, except for HTML

QBF has zero dependencies, uses a standards-based approach, and is beginner-friendly. We aim to support the craftspeople of the web.

<a href="https://www.buymeacoffee.com/"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=☕&slug=earlman&button_colour=BD5FFF&font_colour=ffffff&font_family=Comic&outline_colour=000000&coffee_colour=FFDD00" /></a>


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

- **Leaf Tags**
  - `p`
  - `h1`, `h2`, `h3`, `h4`, `h5`, `h6`
  - `hr`
  - `table`, `thead`, `tr`, `th`, `tbody`
  - `pre > code`
- **Inline Tags**
  - `strong`(bold), `em`(italic), 
     - add: `del`(strikethrough)
  - add: `code`
  - add `a`
  - add `img`
- **Container Tags**
  - `ul`, `ol`, `li`
  - `blockquote`

(currently visible on page)

- `h1`, `h2`, `h3`, `h4`, `h5`, `h6`
- `p`, `strong`(bold), `em`(italic)
- `ul`, `ol`, `li`
- `hr`
- `blockquote > p`
- `pre > code`
- `table`, `thead`, `tr`, `th`, `tbody`
- `form`, `input`, `textarea`, `button` 

There are more tags currently visible on the page, but they may be removed at a later date. It's important we try to keep this lean (but allow options for expansion).

These are based on the [Github Flavored Mardown Spec](https://github.github.com/gfm/). (why that one)[https://github.com/foundations-design/quick-brown-fox/issues/2#issuecomment-1039557401]

## Roadmap 
- [ ] Standardize supported tag list
- [ ] Create extended tag list
- Consider: HTML5 Semantic Entities  
  - Another level of requirements could be based on the [HTML5 Semantic Entities.](https://www.w3schools.com/html/html5_semantic_elements.asp) That's a much more opinionated area, though so it'll be considered at a later date. 







[Some great examples of classless CSS themes](https://github.com/dbohdan/classless-css).

s/o to [sakura](https://github.com/oxalorg/sakura) by @oxalorg

