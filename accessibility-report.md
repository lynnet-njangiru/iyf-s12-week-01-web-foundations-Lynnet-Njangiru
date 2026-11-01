# Accessibility Report

I checked my pages with Lighthouse in Chrome DevTools and with WAVE.

## Problems I found

### 1. The profile image had no alt text

The screen reader could only say "image". I added a description:

```html
<img src="images/profile.svg" alt="Drawing of Lynnet Njangiru" width="180" height="180">
```

I checked the other images too and added alt text where it was missing.

### 2. I skipped a heading level

On `projects.html` I had an `h1` and then used `h3` for the project titles. I
changed the project titles to `h2`, so now it goes h1 then h2.

### 3. One link said "click here"

That does not tell anyone where the link goes. I changed it to "MDN Web Docs".

```html
<a href="https://developer.mozilla.org">MDN Web Docs</a>
```

### 4. The blog page had no language

I added `lang="en"` to the `html` tag on every page so the screen reader knows
which language to use.

### 5. My form inputs needed labels

At first I only used placeholders. A placeholder disappears when you type, so
I added a label for every input:

```html
<label for="email">Email Address</label>
<input type="email" id="email" name="email" required>
```

I also used `fieldset` and `legend` to group the form.

## Other checks

- The black text on a white background has good contrast.
- I can reach the links and form fields with the Tab key.
- The page still works when I zoom to 200%.

## Lighthouse score

My first accessibility score was 82. After fixing the image, the heading and
the link text, the accessibility score was **100**.

## What I learned

It is easier to write good HTML from the start than to fix it later. I will run
Lighthouse after every page I make.
