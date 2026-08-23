# YouTube.com Clone

A responsive **YouTube.com clone** created as a frontend development practice project using **HTML5 and CSS3**. The project focuses on recreating the visual layout and user interface of YouTube, including the header, sidebar, suggestion bar, video grid, thumbnails, channel information, and responsive design.

> **Note:** This is an educational project created for learning and practice purposes. It is not affiliated with or endorsed by YouTube.

## Features

* YouTube-style header
* Search bar and search button
* Sidebar navigation
* Video suggestion/category bar
* Responsive video grid
* Video thumbnails
* Video duration badges
* Channel profile pictures
* Video titles, authors, and view information
* Clickable video preview links
* Clickable channel/profile links
* Navigation using HTML anchor (`<a>`) tags
* External links using `href`
* Responsive layout for different screen sizes
* CSS media queries for responsive design
* YouTube-style favicon
* Organized HTML and CSS structure

## Technologies Used

* **HTML5**
* **CSS3**

## HTML Concepts Used

This project includes:

* HTML semantic elements
* `<div>` elements for layout
* `<header>` for the website header
* `<img>` for images and thumbnails
* `<a>` for links and navigation
* `href` for page and external links
* `<button>` for interface elements
* `<input>` for the search bar
* `<title>` for the browser page title
* `<link rel="icon">` for the favicon

### Example Anchor Link

```html
<a href="https://www.youtube.com/">
    YouTube
</a>
```

Anchor tags are also used for video thumbnails, video titles, and channel profile links.

## CSS Concepts Used

The project uses:

* CSS Grid
* CSS Flexbox
* Media Queries
* `position: relative`
* `position: absolute`
* `display: inline-block`
* `object-fit`
* Responsive sizing
* Margins and padding
* Border radius
* Typography
* CSS selectors
* Hover effects
* Responsive video layouts

## Responsive Design

CSS media queries are used to change the video layout according to the screen size.

Example:

```css
@media (max-width: 720px) {
    .video-grid {
        grid-template-columns: 1fr;
    }
}

@media (min-width: 750px) and (max-width: 1150px) {
    .video-grid {
        grid-template-columns: 1fr 1fr;
    }
}

@media (min-width: 1151px) {
    .video-grid {
        grid-template-columns: 1fr 1fr 1fr;
    }
}
```

This allows the website to adapt to different screen sizes.

## Project Structure

```text
youtube-clone/
│
├── headerElements/
│   └── Header-related images and elements
│
├── images/
│   └── Website images, thumbnails, and channel pictures
│
├── sidebarElements/
│   └── Sidebar-related elements
│
├── styles/
│   ├── general.css
│   ├── header.css
│   ├── sidebar.css
│   ├── video.css
│   └── suggestions.css
│
├── index.html
│
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/youtube-clone.git
```

### 2. Open the project

Open the project folder in **Visual Studio Code**.

### 3. Run the project

Open `index.html` using the **Live Server** extension in VS Code.

The project will then open in your browser.

## What I Learned

While creating this project, I practiced:

* Building webpages using HTML5
* Styling webpages using CSS3
* Creating layouts with CSS Grid
* Using Flexbox
* Working with CSS media queries
* Making webpages responsive
* Positioning elements using CSS
* Working with images and thumbnails
* Creating video duration badges
* Using anchor tags and `href`
* Linking video previews to external pages
* Linking channel/profile pictures
* Organizing HTML and CSS files
* Creating a YouTube-style user interface

## Current Project Status

This project currently focuses on the **frontend design and layout**.

It does not currently include JavaScript functionality or backend integration.

## Future Improvements

Possible future improvements include:

* Add JavaScript functionality
* Add a functional search system
* Add video playback
* Add dynamic video content
* Add interactive sidebar functionality
* Add dark mode
* Add user authentication
* Add backend integration
* Add database support

## Author

**Subha Nandi**

BCA Student
Interested in Software Development, Web Development, and Data Structures & Algorithms.

## Disclaimer

This project is created for educational and practice purposes. It is a frontend recreation of a familiar video-platform interface and is not an official YouTube product.
