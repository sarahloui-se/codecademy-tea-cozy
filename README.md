# Codecademy Off-Platform Project: Tea Cozy
Created as part of Codecademy's Learn Intermediate CSS course.

## Key details in code
* Card containers
  - Featured tea cards (`.card-tea`)
  - Store cards (`.card-store`)
* `<address>` in footer

###  Card containers
A card component in design is a single, contained unit that can be repeated. They are commonly developed as part of a pattern library: [a library of UI and design pattern "solutions" for solving design problems](https://www.aiimi.com/insights/guide-to-pattern-libraries-the-key-to-design-consistency).

Tea Cozy's design makes use of two cards:
- #### Featured tea cards (`.card-tea`)  
`<figure>` containing `<img>` and `<figcaption>`. Used as the feature tea cards are self-contained.
- #### Store cards (`.card-store`)  
Uses the [h-card microformat](http://microformats.org/wiki/h-card) to mark up store locations.

### `<address>` in footer
[Per HTML5 specification](https://html.spec.whatwg.org/multipage/sections.html#the-address-element), `<address>` is used to indicate the contact information for its nearest `<article>` or `<body>` element ancestor. In this instance, `<address>` indicates the contact information for the page.

## To-Do list
* Replace `<h4>` with `<p class="tagline">` and matching CSS to improve semantics
* Mark up email and phone number in footer
* Replace PX with (R)EM units for improved accessiblity and responsiveness
* Begin adding CSS