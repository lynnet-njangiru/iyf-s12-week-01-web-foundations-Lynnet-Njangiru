# Week 1: Web Foundations

## Author
- **Name:** Lynnet Njangiru
- **GitHub:** [@lynnnjangiru](https://github.com/lynnnjangiru)
- **Date:** October 30, 2026

## Project Description

This is my first portfolio website for IYF Weekend Academy. It has a home page,
an about page, a projects page and a contact page. I also made a semantic blog
page, wrote my DevTools answers and did an accessibility check.

I built the pages with plain HTML. The CSS comes in Week 2.

## Technologies Used

- HTML5
- GitHub Pages
- Chrome DevTools
- WAVE accessibility tool

## Features

- Four pages with the same navigation
- The current page is shown in bold
- A profile image with alt text
- A contact form with labels and validation
- A semantic HTML version of the blog layout
- Five daily challenge pages
- A DevTools report and an accessibility report

## How to Run

1. Clone the repository.
2. Open `index.html` in your browser.
3. Or open the folder in VS Code and use Live Server.
4. Use the navigation to move between pages.

## Project Structure

```
week-01-web-foundations/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── semantic-conversion.html
├── devtools-exploration.md
├── accessibility-report.md
├── images/
│   └── profile.svg
├── daily-challenges/
│   ├── day-1-five-tags.html
│   ├── day-2-navigation.html
│   ├── day-3-contact-section.html
│   ├── day-4-photo-gallery.html
│   └── day-5-blog-post.html
└── README.md
```

## Lessons Learned

- A page needs a doctype, an `html` tag with a language, a head and a body.
- Tags like `header`, `nav`, `main`, `article` and `footer` describe the page
  better than using `div` for everything.
- Every form input needs a label.
- `required` and `minlength` make the browser check the form.
- `alt` text tells someone what an image shows.
- GitHub Pages can host plain HTML files.

## Challenges Faced

**The navigation was only on one page.** I copied the same header into every
page. It is a lot of copying, but I understand it now.

**Some links did not work.** I opened a file inside `daily-challenges/` and the
link to `index.html` failed. I changed it to `../index.html` and it worked.

**I did not take the DevTools screenshot.** I was using the school computer and
could not save it. I will add it when I get a chance.

## Live Demo

[View Live Site](https://lynnnjangiru.github.io/iyf-s12-week-01-lynnnjangiru)

## Reports

- [DevTools exploration](devtools-exploration.md)
- [Accessibility report](accessibility-report.md)
