# Skelter Sass

December 17, 1996 - [W3C releases CSS 1.0 Recommendation](https://www.w3.org/Press/CSS1-REC-PR.html)

## Who here has worked on a project where the CSS was hard to maintain?
## Who has written CSS that's hard to maintain?

## Why is CSS so hard?

  - Limited structure
  - No enforced conventions
    - layout, colors, sizes are all the same
  - Everything is open

# SASS

  - [What is Sass?](http://sass-lang.com/)
    - A compile-to-css extension language
    - CSS compatable
    - Originally written in ruby (slow)
    - Now there's libscss
    - Two flavors `.scss` and `.sass` (we will use .scss)
    - It wont solve your css problems

  - Sass Features
    - @import
    - variables
    - Nested selectors
    - Parent selector `&`
    - Functions/Mixins

  - Best practices
    - Don't use @extend
    - Create a top-level manifest with @imports only (Gabe is doing this)
    - Don't nest deeply (3 levels max)
    - Think about "components" not about "pages"
      - Methodologies
        - BEM
        - SMACS
        - OOCSS
      - Frameworks
        - Bootstrap
        - Foundation
        - Angular Material
        - Inuit CSS


Pages:

  20 years
  Pattern Library
  BEM
  SMACS
  Angular Material SCSS
  Bootstrap SCSS
