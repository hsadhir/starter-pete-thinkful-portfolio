# starter-pete-thinkful-portfolio

This portfolio is designed based on the requirements provided for Deeper with CSS section of Thinkful Web Dev Fundamentals Course.

## Header Redesign

- Logo Text and Navigation Bar was horizontally aligned on a single row by making their parent container (Header) a Flex (`display: flex`) and giving both `h1` and `nav`, a `flex` property of `1`, so that they both take equal width within the flex container.
- In order to make the logo text and navigation bar vertically centered within the header container, `align-items: center` property was applied to the `header` flex container.

## About Section Redesign

- Pete's Image and *Hi, I am Pete Thinkful* sections were put up inside a Flex container in order to display them horizontally in the same row.

## Portfolio Section Redesign

- All portfolio projects have been horizontally aligned in a single row by using a flex container.

- All project descriptions have been given a `font-14` class and a css property of `font-size: 14px` in order to modify their default font sizes to 14px.

## Other customization

- Played with colors in the portfolio, and used "Nord Theme" colors to give the portfolio a dark mode feel. (Did this because there wasn't any project requirement sorrounding the colors).
- In project code, created separate CSS files in the `styles/` folder, and imported them in style.css using `@import` syntax. This was done to make the project better organized.