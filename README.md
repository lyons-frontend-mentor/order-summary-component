# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

### Links

- [Solution](https://www.frontendmentor.io/solutions/learning-tailwind-5-ryT8OXJ8c)
- [Live Site](https://lyons-frontend-mentor.github.io/order-summary-component/)

### Built with

- HTML
- TailwindCSS

## Reflection

Not much new here. However, this was the first Frontend Mentor challenge that I attempted last year back in August, and I remember struggling a lot with the subscription plan section (the flex box beneath the body text). It's satisfying that it felt so simple to create this time, now that I have a good understanding of Flexbox. Back then, I struggled a lot spacing out the "Annual Plan $59.99/year" from the rest of the content, but now I realize that all I needed was `flex-grow`.

Though it wasn't in the Figma design, I added extra styling for when the user navigates to the "Change" link via keyboard. On the one hand, the underline pre-focus/hover helps indicate that "Change" is interactive. On the other hand, I don't feel that having the underline disappear on focus gives enough visual feedback to the user (for hover it's OK, since they're aware that they're trying to hover over the button, so they'll most likely see the change). Thus, I added a dashed outline on `:focus-visible`. In the real-world, it's probably best in these cases to consult with the designer first for such a change.

### Continued development

I will continue practicing Tailwind on challenges of this level for a while longer.
