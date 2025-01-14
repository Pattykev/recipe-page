# Frontend Mentor - Social-links-profile

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%20from%202025-01-14%2012-55-28.png)



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned
 - How to modify items of non-numeroted and numeroted lists
 
 `ol or ul li::before {
    content: "•";
    color: var(--Brown); 
}
 `

 - Explanation


**Selector (ul li::before):** This specifies that the styles within the curly braces apply to the ::before pseudo-element of each list item (li) that is a child of an unordered list (ul). The ::before pseudo-element allows you to insert content before the actual content of the list item.

**content: "•";:** This property sets the content that will be inserted before each list item. In this case, it's a bullet point (•). This means that instead of the default bullet style provided by the browser, a custom bullet (the specified character) will be used.

**color: var(--Brown);:** This property sets the color of the inserted bullet point. The value var(--Brown) indicates that the color is being set using a CSS custom property (also known as a CSS variable) named --Brown. This allows for easy changes to the color throughout the CSS by just changing the value of the variable in one place.


