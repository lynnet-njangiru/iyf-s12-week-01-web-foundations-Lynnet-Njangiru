# DevTools Exploration

I used Chrome. I right-clicked on each page and chose Inspect.

## Website 1: example.com

**Tags:** `html`, `head`, `title`, `meta`, `body`, `div`, `h1`, `p`, `a`.
Most of the page is inside one `div`.

**Page title:** Example Domain.

**Headings:** There is only one heading, an `h1` that says "Example Domain".

## Website 2: developer.mozilla.org

**Navigation:** The main menu is inside a `<nav>` tag. The links are in a
`<ul>` and each link is an `<a>`.

**Search bar:** It is in a `<form>`. I saw an `<input>` for the words and a
`<button>` next to it. There was also some text inside the input to show what
to type.

**Hover:** When I hover a link, it changes colour and gets an underline. In the
Styles panel I could see that this comes from a `:hover` rule.

## Website 3: Wikipedia

**Five elements:** I found `<header>`, `<nav>`, `<main>`, `<section>` and
`<footer>`. There were also normal tags like `<a>`, `<h1>`, `<img>` and `<form>`.

**Form and inputs:** The language search form has a text input, a submit button
and a hidden input for the chosen language.

**Screenshot:** I could not save a screenshot on the school computer. I drew the
tree I saw instead:

```
html
└── body
    ├── header
    ├── main
    │   └── section
    └── footer
```

I will add the real screenshot later as `images/devtools-elements.png`.

## What I learned

The Elements panel shows the HTML that the browser is really using. The Styles
panel shows which CSS rule is affecting an element. It is easier than guessing.
