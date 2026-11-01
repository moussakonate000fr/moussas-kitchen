# Moussa's Kitchen

Live site: https://moussakonate000fr.github.io/moussas-kitchen/
## Table of contents
- [Purpose](#purpose)
- [Features](#features)
- [Testing](#testing)
- [Bugs and errors](#bugs-and-errors)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [Declaration of AI use](#declaration-of-ai-use)

## Purpose

Moussa's Kitchen is a website for a small restaurant serving home-cooked dishes made from fresh, local ingredients. It lets customers see the menu and contact the restaurant to book a table or ask a question, on phone, tablet or desktop.

## Features
- **Navigation bar** on every page: visitors can move between Home, Menu and Contact easily.
- **Hero section** on the home page: shows what the restaurant is about straight away.
- **Menu cards** with a "New" badge: dishes are easy to read and new items stand out.
- **Contact form** with labelled fields: customers can send a message in one place.
- **Responsive layout**: the site works on mobile, tablet and desktop.

## Testing
| Test | Page | Result |
|---|---|---|
| W3C HTML validator | Home, Menu, Contact | No errors or warnings |
| W3C Jigsaw CSS validator | style.css | No errors |
| Lighthouse (mobile) | Home, Menu, Contact | Performance 95, Accessibility 100, Best Practices 100, SEO 100 |
| Manual link check | All pages | Every nav link and button works |
| Responsive check | All pages | Tested at 375px, 768px and 1280px in DevTools, and on an iPhone |

## Bugs and errors
- **Styles missing on the live site:** I first uploaded the files without the assets folder. Fix: dragged the whole assets folder into the upload.
- **Lighthouse SEO 91:** the pages had no meta description. Fix: added a meta description to the head of each page (SEO now 100).
- **Badge in the wrong place:** the "New" badge moved to the edge of the page. Fix: added position: relative to .card so the badge sits inside the card.
- **Hero not centred:** the text sat side by side. Fix: added flex-direction: column to .hero.

## Deployment
1. Created a public repository on GitHub called moussas-kitchen.
2. Uploaded index.html, menu.html, contact.html and the assets folder.
3. Went to Settings > Pages, chose Deploy from a branch, main, / (root), and clicked Save.
4. After a minute the site was live at https://moussakonate000fr.github.io/moussas-kitchen/

## Screenshots
Screenshots of each page on desktop and mobile will be added here.

## Credits
- Font: Poppins from Google Fonts.
- Roast chicken image: free stock photo (source to be confirmed).
- Layout help: Bootstrap 5.3 documentation and W3Schools.

## Declaration of AI use
I used Claude (an AI assistant) as a tutor while building this site, to explain concepts step by step and to check my code from screenshots. I wrote and placed the code myself.
