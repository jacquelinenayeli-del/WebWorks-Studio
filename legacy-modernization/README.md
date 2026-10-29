# Southtown Plant Co. — Week 2 Inherited Client Site

## Change - Why 

WebWorks Studio has inherited this small-business website from a previous developer.

The site is functional, but the underlying front-end code reflects practices common in older websites. Your assignment is to modernize the code while preserving the client's content and general visual identity.

## Before You Edit
1. Keep an untouched copy of this starter project.
2. Put your working copy in:
   `webworks-studio/week02-build-better/`
3. Open the entire project folder in Visual Studio Code.
4. Preview `index.html` in a browser.
5. Resize the browser window and observe the existing behavior before you change anything.

## Important
The inherited site is intentionally **not responsive**.

Do not simply redesign the site from scratch. Refactor it according to the requirements in the Week 2 Canvas assignment.

## Preserve
- Client content
- General color palette and visual identity
- Working navigation and links
- Meaningful image alternative text
- Required site information

## Your Goal
Make the code easier for another developer to understand, maintain, and extend.

Refer to the Canvas assignment for all required technical work, GitHub workflow, and submission directions.
---

## Week 3 — Responsive Overhaul

### Decision 1: Responsive Navigation

**Problem:**1. Navigation	The old six-cell table

**Solution:**Flexbox and wrapping

**Why:** 
I replaced the old navigation table with a <nav> elemnt and used CSS Flexbox to arrange the links. I added flex-wrap, wrap so the navigation links can move to another line when the browser window gets smaller.

### Decision 2: Introduction and Patio Image

**Problem:**fixed 420px and 280px columns

**Solution:**Grid and stacking

**Why:** replacing the fixed-width table containing the introduction and patio image with a CSS Grid layout. I added a media query so the text and image appear side by side on larger screens and stack vertically on smaller screens.

### Decision 3: Responsive Plant Cards

**Problem:**old 720px table

**Solution:**converted the three descriptions into Grid cards

**Why:****Solution:** I replaced the old table containing the three plant descriptions with individual cards using `<div>` elements. I used CSS Grid and a media query to display three columns on larger screens and one column on smaller screens.

## CSS Grid Implementation


## Flexbox Implementation


## Live Website URL