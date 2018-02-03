# My Version of the restaurant website.

## Motivation

As developed in Lecture 30 and following of the HTML, CSS, and JavaScript course.
I was watching the lectures and not really feeling like I was getting much out of
it, so I decided to code my own version of the website in parallel with the videos.

This is what that is.

## Starting point

I started with the contents of the `Lecture30/after` folder. This contains

* Bootstrap v3.3.6 (`css` and `js` files)
* `css/styles.css` containing color, background-color, font-size, and font-family styling for the `body` Starting
* Varous `glyphicons` font files
* `jquery-2.1.4.min.js`
* `npm.js` which contains a bunch of `require` entries to files not included in the course Git repository
* An empty `js/script.js`
* A skeleton `index.html` page

To which I have added this README.md file.

## Lecture 30, Part 1: Coding Basics of Navbar Header

### Code modification:

* Added initial `header` / `nav` / `div container` structure to `index.html`.
* Styled `#header-nav`
* added logo image div with link
* styled `#logo-img`, copied over logo images

### Bootstrap elements:

* `navbar` and `navbar-default`, `navbar-header` classes
* [Bootstrap navbar documentation](getbootstrap.com/components/#navbar)

### CSS styles

* `border-radius`

## Lecture 30, Part 2: Navbar Header basics continued

### Code modification

* Added "Kosher Certified" image and text, styled logo anchor to `pull-left`
* Import Lora font, styling `navbar-brand`
* added `visible-md` and `visible-large` to logo image

### Bootstrap elements:

* `navbar-brand`, `pull-left`

### CSS stylesheet

* `text-transform`, `text-shadow`, `line-height`, `text-decoration`
