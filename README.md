# Horiseon
![Screenshot of Horiseon page top](./screenshots/pagetop-screenshot.jpg)
![Screenshot of Horiseon page content](./screenshots/content-screenshot.jpg)

---

## Purpose
A website for advertising services offered by Horiseon marketing agency.

---

### Table of Contents
You're sections headers will be used to reference location of destination.

- [Built With](#built-with)
- [Website](#website)
- [Contribution](#contribution)
    - [Author Contact Info](#author-contact-info)
- [Changes From Original Version](#changes-from-original-version)
    - [Added](#added)
    - [Changed](#changed)
    - [Removed](#removed)
    - [Fixed](#fixed)

[Back to Top](#Horiseon)

---

## Built With
HTML
CSS

[Back to Contents](#table-of-contents)

---

## Website
https://craig5117.github.io/Horiseon/

[Back to Contents](#table-of-contents)

---

## Contribution
Original version supplied by Horiseon marketing agency. Original contributors unknown.

This version refactored and published by **Craig Bennett**.


### Author Contact Info:

GitHub: https://github.com/Craig5117

Facebook: https://www.facebook.com/craig.bennett.5817/

LinkedIn: https://www.linkedin.com/in/craig-bennett-852a571b4/

[Back to Contents](#table-of-contents)

---

## Changes From Original Version
2020-10-04

### Added
- Notes for better readability in index.html.
- Note for better readability in style.css. 
- Alternative text to images for better accessibility and compatibility with screen readers.
- Alternative text to background image in the hero section.
- Link to landing page on the Horiseon logo.
- Page title.
- id attribute on Search Engine Optimization article (this fixed the broken link in the header section).
- Float-left/float-right classes to the 3 div containers under content section. This fixed issues with text moving when resizing the browser. 
- Width parameters to content section and min-width to body to fix text overflow issues when resizing the browser.

### Changed
- Replaced several div tags with more descriptive tags (header, footer, article, section, nav).
- Reorganized css by section and ordered selectors by semantic structure.
- Consolidated css for Content section (the .content div, h2, and img selectors previously were represented by 9 different selectors, but this has been reduced to 3). This reduces the code size for style.css and improves page load time.
- Consolidated css for Benefits section (the .benefits div, h3, and img selectors previously were represented by 9 different selectors, but this has been reduced to 3). This reduces the code size for style.css and improves page load time.
- Resized font, padding, and marginis for text, images, and sections to better fit the client's provided mock-up. 
- Optimized file size for images to improve page loading time. The 3 images under Content were scaled down to double the display size on the page. The background image for the header was scaled down to HD resolution. These images were also compressed and the current file size is now less than 3% of the original, without any noticeable loss in quality. The result is that the page loads much faster now. 

### Removed
- Closing img tag from the image found under Cost Management. This tag was no longer necessary and removing it improves page loading time.
- Unused classes under Content and Benefits sections (made obsolete by the consolidation of the css code).

### Fixed
- Search Engine Optimization link.
- Page loading very slowly.

[Back to Contents](#table-of-contents)