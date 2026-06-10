# Blog Preview Card

This project is a simple blog preview card created using HTML and CSS. It is based on a Frontend Mentor challenge and demonstrates responsive styling, semantic HTML structure, and basic accessibility enhancements.

## Project Overview

- A centered card layout with an illustration, category tag, publication details, title, description, and author section.
- Responsive container width using `min(80vw, 350px)` and flexible image sizing.
- Styled directly in the `index.html` file using an internal `<style>` block.

## Semantic HTML Usage

The page uses semantic HTML to describe the content clearly:

- `<!DOCTYPE html>` and `<html lang="en">` define the document type and language.
- `<head>` includes metadata, viewport settings, and font loading.
- `<body>` contains the main card content.
- The `.container` element wraps the card content, while nested `<div>` elements group related parts.
- `<h1>` is used for the article title, which is the main heading of the card.
- `<p>` elements are used for the category tag, publish date, description, and author name.

## Accessibility Enhancements

This project includes several accessibility-friendly attributes:

- `alt` attributes on images provide text descriptions for screen readers.
- `role="img"` and `aria-label` were added to the image container to describe the illustration.
- `role="group"` and `aria-label` are used to group related content sections.
- `role="button"` and `aria-pressed="false"` are applied to the category tag to indicate interactive intent.
- `role="heading" aria-level="1"` is used on the main title to reinforce the document structure.

## Notes

- This project is intended for learning and practice, so styles and structure are kept simple.
- Semantic HTML and explicit ARIA labels help make the content easier to navigate for assistive technologies.
- The card layout is designed to adapt to smaller screen widths while keeping the content readable.

## Files

- `index.html` — Main markup and styles for the blog preview card.
- `images/` — Image assets used in the card layout.

Enjoy practicing and building on this Frontend Mentor challenge! Feel free to extend it with more responsive breakpoints, improved accessibility, or separate CSS files for cleaner styling.