# **Horiseon Code Refactoring Project**

This is my introductory challenge for my full-stack web development bootcamp. The goal of this project is to refactor the given starter code and make improvements in the following areas:

* Overall Website Accessibility
* Semantic Structure
* Code Cleanup

## Overall Website Accessibility

For greater accessibility, the images in the ‘section’ and ‘aside’ elements have all been assigned an alt tag with an appropriate title.

## Semantic Structure

Most div tags have been reassigned to a new semantic tag. The new tags better define the respective role of each element. These tags enhance search engine results for the site and make the code easier to comprehend when reviewed.

## Code Cleanup
Major opportunities for improvement were found in the starter code's html anchor tags and the organization of the style sheet. The link for ‘Search Engine Optimization’ was not functioning and now navigates to the appropriate location. Selectors with the same specification were consolidated into a single selector when possible to avoid redundancies. 

The changes to the HTML’s semantic structure also had an influence on the stylesheet. The naming of our ‘header’ and ‘footer’ lets us change those respective class selectors to element selectors instead. The structure of the CSS layout has also been reordered so that the flow of the stylesheet matches the order of our HTML semantic tags. This makes the code more organized and simpler to review when consulting both files.


### Deployed Website Example

[You can find a deployed version of the website here](https://littmarque27.github.io/Horiseon-Accessibility-and-Semantics-Enhancements/) or review the screenshot below.

![Full Site Screenshot](./assets/images/Full-Site-Screenshot.png)


