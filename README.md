# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

# Overview
My challenge was to build out this card component and get it looking as close to the design as possible. (design dan be found in folder titled 'design')

The site should be responsive to two screen widths 375px and 1440px.
## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://github.com/Tyson-Wellings/stats-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://tyson-wellings.github.io/stats-preview-card-component-main/)

## My process

I first added appropriate divs after considering how the content will be best arranged to fit the layouts required. I semantically tagged the elements using the appropriate tags such as h1 h2 p etc. There weren't many components for this simple project. After html was written I then added the CSS to style everything according to the design. The mobile layout was programmed first then the appropriate media query for the desktop layout was created and the desktop layout was made. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This program reinforced to me the importance of mobile first design. I initially made the desktop layout first then attempted to make it responsive afterwoods. This proved alot harder than starting with the mobile layout and then having a few changes within the media query. I want to continue to experiment with this to see if it is a consisted trend I'm noticing. I personally only utilzed flex box and percentage values for widths and paddings however I do want to experiment with grid as I am not comfortable with grid and I noticed other people used grid in their solution. 

I was having trouble with the image not appearing. The image was indeed present however the container had 0 height. I cannot remember how this was resolved however once the container worked I kept having a 4 pixel discrepancy between the height of the container and the image. I fixed this issue by making the image an inline-block.


### Useful resources

- [Centering Guide](https://css-tricks.com/centering-css-complete-guide/#vertical-inline-single) - This helped me center elements. It has different methods for different use cases. Very succinct and handy
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - THe best flex box guide. I always find myself going back to this. It is probably why I feel so comfortable relying on flexbox.

## Author

- Frontend Mentor - [@Tyson-Wellings](https://www.frontendmentor.io/profile/Tyson-Wellings)


