# Coding Exercise: Adding a Meta Description and Favicon

In this coding exercise, you will learn more about the HTML `<head>` element and add two useful items to it: a **meta description** and a **favicon**.

You have already been using the `<head>` section all semester, even if you have not spent much time thinking about it directly. The `<head>` contains information **about** a webpage rather than the visible page content visitors read in the browser window. This is where we place things like the page title, character encoding, viewport settings, and links to stylesheets.

In this exercise, you will build on that knowledge by adding two more common and useful pieces of information to the `<head>`:

- A **meta description**, which is a short summary of what a webpage is about
- A **favicon**, which is the small icon that appears in a browser tab next to the page title

These are small details, but they help make a website feel more complete and professional.

---

## Learning Goals

By completing this exercise, you will:

- review the purpose of the HTML `<head>` element
- practice reading and editing code inside the `<head>`
- add a meta description using a `<meta>` tag
- add a favicon using a `<link>` tag
- strengthen your understanding of file paths and linked resources

---

## Project Files

This project includes the following files:

- `index.html`  
  The main HTML page for the exercise

- `reset.css`  
  A reset stylesheet to help create a more consistent starting point

- `styles.css`  
  The main stylesheet for the example page

- `images/uc-favicon.png`  
  The image file you will use as the favicon

---

## Before You Start

1. Download or clone this repository.
2. Open the project folder in **Visual Studio Code**.
3. Open `index.html` in your browser so you can see the starting version of the page.
4. Read through the content on the page so you understand what it is teaching about the `<head>` element.

---

## What You Need to Do

Your job is to edit the `<head>` section of `index.html` and add **two new lines of code** in the correct places.

Inside the `<head>`, you will see these comments:

```html
<!-- Add a meta description below this comment -->

<!-- Add a favicon below this comment -->
```

Add the correct code below each comment.

### 1. Add a Meta Description

A meta description is a short summary of what a webpage is about.

It is placed inside the `<head>` and is not shown as normal page content. Search engines like Google may use this text as part of the page snippet in search results.

Add a meta description below the comment provided.

A basic example looks like this:

```html
<meta name="description" content="A short summary of this webpage.">
```

Write a description that fits **this page**.

### 2. Add a Favicon

A favicon is the small icon that appears in a browser tab next to the page title.

For this exercise, the favicon image file has already been included for you in the `images` folder. Your job is to link to it correctly inside the `<head>`.

A basic example looks like this:

```html
<link rel="icon" href="images/uc-favicon.png" type="image/png">
```

Add the favicon link below the comment provided in the HTML file.

---

## Important Notes

- Both new lines of code must be added **inside the `<head>` element**
- Be careful with spelling and punctuation
- Make sure the file path for the favicon is correct
- The favicon may not appear immediately if your browser is caching the page, so try refreshing again if needed

---

## Suggested Workflow

A good step-by-step process would be:

1. Open `index.html`
2. Locate the comments in the `<head>`
3. Add the meta description
4. Add the favicon link
5. Save the file
6. Refresh the page in your browser
7. Check the browser tab to see whether the favicon appears
8. Commit and push your changes to GitHub

---

## Troubleshooting Tips

If something is not working, check the following:

### The favicon is not showing up

- Make sure the `<link rel="icon">` line is inside the `<head>`
- Make sure the file path matches the actual file location
- Make sure the image filename is spelled correctly
- Refresh the browser again
- Try closing and reopening the browser tab if needed

### The page looks broken

- Make sure you did not accidentally delete part of the existing `<head>`
- Check that your new tags are typed correctly
- Make sure quotation marks, angle brackets, and slashes are all in the right places

### The meta description is not visible on the page

That is normal. A meta description is **not** shown as regular content in the page body.

---


## Optional Follow-Up

After completing this exercise, try adding a favicon to your **final project website** as well.

That's is not required for this coding exercise, but it is a nice way to make your final project feel a little more polished.

