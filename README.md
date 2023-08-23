# grid_template
hosted link 
https://ajit7568.github.io/grid_template/
![Screenshot (81)](https://github.com/ajit7568/grid_template/assets/104454960/c1b2e5a6-e7df-4a46-ac13-28585eb433c7)
various CSS custom properties (variables) and uses them to style different components of a webpage. Here are the CSS properties used in the code:

:root: This selector defines CSS custom properties (variables) within the root element.

--clr-primary-400, --clr-secondary-400, etc.: These are custom properties that define color values in HSL format.

--ff-primary: This custom property defines the font family for the primary text.

--fw-400, --fw-700: These custom properties define font weights for different text elements.

--fs-300, --fs-400, --fs-500: These custom properties define font sizes for different text elements.

*, *::before, *::after: These selectors apply box-sizing: border-box to all elements and pseudo-elements.

body, h1, h2, h3, h4, p, figure, blockquote, dl, dd: These selectors remove margin from various elements.

ul[role="list"], ol[role="list"]: This selector removes list-style for unordered and ordered lists with a specific role.

html:focus-within: This selector sets smooth scroll behavior when an element within html receives focus.

body: This selector sets various properties for the body element, including font, background color, and text-related properties.

a:not([class]): This selector styles anchor elements without a class to skip ink when underlined.

img, picture: These selectors define properties for images and pictures.

input, button, textarea, select: These selectors inherit fonts for input and button elements.

@media (prefers-reduced-motion: reduce): This media query targets users who prefer reduced motion and removes animations and transitions.

.flex, .flow: These are utility classes for flex display and vertical spacing.

.bg-primary-400, .bg-secondary-400, etc.: These classes define background colors using the custom properties.

.text-neutral-100, .text-secondary-400: These classes define text colors using the custom properties.

.border-primary-400: This class defines a border color for an element.

.testimonial-grid, .testimonial: These classes define styles for a grid layout and testimonials.

Various media queries (@media screen and (min-width: ...)) target different screen sizes to adjust the layout and grid template areas.

.testimonial.quote: This class adds a background image to testimonials.

.testimonial img, .testimonial .name, .testimonial .position: These classes define styles for images, name, and position within testimonials.

.testimonial > p:first-of-type, .testimonial > p:last-of-type: These selectors style the first and last paragraphs within testimonials.
