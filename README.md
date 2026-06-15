# CSS Interview Questions & Answers

> A curated list of CSS interview questions covering Fundamentals & Selectors, Box Model & Layout, Units & Colors, Typography & Text, Display & Visibility, Positioning, Flexbox, CSS Grid, Responsive Design & Media/Container Queries, Pseudo-classes & Pseudo-elements, and Transitions, Animations, Transforms, Performance & Architecture — each with a clear explanation and code example where applicable.

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions |
| --- | --------- |
|     | **Fundamentals & Selectors** |
| 1 | [What is CSS and why is it used?](#what-is-css-and-why-is-it-used) |
| 2 | [How do you include CSS in a page?](#how-do-you-include-css-in-a-page) |
| 3 | [What is the CSS cascade?](#what-is-the-css-cascade) |
| 4 | [Explain selector specificity.](#explain-selector-specificity) |
| 5 | [Difference between id, class and element selectors?](#difference-between-id-class-and-element-selectors) |
| 6 | [What is the universal selector?](#what-is-the-universal-selector) |
| 7 | [What are grouping selectors?](#what-are-grouping-selectors) |
| 8 | [Describe descendant selectors.](#describe-descendant-selectors) |
| 9 | [Difference between child and descendant selectors?](#difference-between-child-and-descendant-selectors) |
| 10 | [Adjacent sibling vs. general sibling selectors?](#adjacent-sibling-vs-general-sibling-selectors) |
| 11 | [What are attribute selectors?](#what-are-attribute-selectors) |
| 12 | [What does !important do?](#what-does-important-do) |
| 13 | [Which properties are inherited by default?](#which-properties-are-inherited-by-default) |
| 14 | [What is the default user agent stylesheet?](#what-is-the-default-user-agent-stylesheet) |
| 15 | [What is the difference between inline, internal and external CSS?](#what-is-the-difference-between-inline-internal-and-external-css) |
| 16 | [Explain the :root pseudo-class.](#explain-the-root-pseudo-class) |
| 17 | [What is a combinator?](#what-is-a-combinator) |
| 18 | [What is the difference between :nth-child() and :nth-of-type()?](#what-is-the-difference-between-nth-child-and-nth-of-type) |
| 19 | [What are pseudo-classes?](#what-are-pseudo-classes) |
| 20 | [What are pseudo-elements?](#what-are-pseudo-elements) |
|     | **Box Model & Layout** |
| 21 | [Explain the CSS box model.](#explain-the-css-box-model) |
| 22 | [Difference between padding and margin?](#difference-between-padding-and-margin) |
| 23 | [What is margin collapsing?](#what-is-margin-collapsing) |
| 24 | [How can you prevent margin collapsing?](#how-can-you-prevent-margin-collapsing) |
| 25 | [Explain box-sizing.](#explain-box-sizing) |
| 26 | [Why is box-sizing: border-box preferred?](#why-is-box-sizing-border-box-preferred) |
| 27 | [Difference between min-width, width, and max-width?](#difference-between-min-width-width-and-max-width) |
| 28 | [How do overflow values differ?](#how-do-overflow-values-differ) |
| 29 | [How to create a scrollable container?](#how-to-create-a-scrollable-container) |
| 30 | [Does outline affect layout?](#does-outline-affect-layout) |
| 31 | [What is percentage width?](#what-is-percentage-width) |
| 32 | [What happens when content overflows its container?](#what-happens-when-content-overflows-its-container) |
| 33 | [Difference between margin shorthand and individual sides?](#difference-between-margin-shorthand-and-individual-sides) |
| 34 | [When does margin collapsing happen?](#when-does-margin-collapsing-happen) |
| 35 | [How do you center a block element horizontally?](#how-do-you-center-a-block-element-horizontally) |
| 36 | [What is clearfix?](#what-is-clearfix) |
| 37 | [Difference between display: none and visibility: hidden?](#difference-between-display-none-and-visibility-hidden) |
| 38 | [Describe display: contents.](#describe-display-contents) |
| 39 | [What is display: flow-root?](#what-is-display-flow-root) |
| 40 | [Can inline elements have width/height?](#can-inline-elements-have-widthheight) |
|     | **Units & Colors** |
| 41 | [Absolute vs. relative units?](#absolute-vs-relative-units) |
| 42 | [Difference between px, %, em and rem?](#difference-between-px--em-and-rem) |
| 43 | [Difference between em and rem when used on font-size?](#difference-between-em-and-rem-when-used-on-font-size) |
| 44 | [What are viewport units?](#what-are-viewport-units) |
| 45 | [When should you use rem instead of px?](#when-should-you-use-rem-instead-of-px) |
| 46 | [How does percentage height work?](#how-does-percentage-height-work) |
| 47 | [What is the ch unit?](#what-is-the-ch-unit) |
| 48 | [What is the ex unit?](#what-is-the-ex-unit) |
| 49 | [What is the fr unit in CSS Grid?](#what-is-the-fr-unit-in-css-grid) |
| 50 | [How do CSS custom units differ from CSS variables?](#how-do-css-custom-units-differ-from-css-variables) |
| 51 | [What is the alpha channel in RGBA/HSLA colors?](#what-is-the-alpha-channel-in-rgbahsla-colors) |
| 52 | [Difference between opacity and alpha channel?](#difference-between-opacity-and-alpha-channel) |
| 53 | [What are gradients?](#what-are-gradients) |
| 54 | [Difference between background-size: cover and contain?](#difference-between-background-size-cover-and-contain) |
| 55 | [How do you set multiple background images?](#how-do-you-set-multiple-background-images) |
| 56 | [What is a conic gradient?](#what-is-a-conic-gradient) |
| 57 | [How do you create a transparent background?](#how-do-you-create-a-transparent-background) |
| 58 | [What does currentColor do?](#what-does-currentcolor-do) |
| 59 | [How do you implement dark mode with CSS variables?](#how-do-you-implement-dark-mode-with-css-variables) |
| 60 | [Explain the background shorthand.](#explain-the-background-shorthand) |
|     | **Typography & Text** |
| 61 | [What is the difference between font-family, font-size, and font-weight?](#what-is-the-difference-between-font-family-font-size-and-font-weight) |
| 62 | [What are web-safe fonts?](#what-are-web-safe-fonts) |
| 63 | [What is @font-face?](#what-is-font-face) |
| 64 | [Difference between serif, sans-serif, monospace and cursive fonts?](#difference-between-serif-sans-serif-monospace-and-cursive-fonts) |
| 65 | [What is line-height?](#what-is-line-height) |
| 66 | [Difference between line-height: normal, unitless and fixed values?](#difference-between-line-height-normal-unitless-and-fixed-values) |
| 67 | [What is letter spacing?](#what-is-letter-spacing) |
| 68 | [What is word spacing?](#what-is-word-spacing) |
| 69 | [What does text-align do?](#what-does-text-align-do) |
| 70 | [Difference between text-decoration and text-transform?](#difference-between-text-decoration-and-text-transform) |
| 71 | [What does white-space control?](#what-does-white-space-control) |
| 72 | [How do you truncate text with ellipsis?](#how-do-you-truncate-text-with-ellipsis) |
| 73 | [What is vertical-align?](#what-is-vertical-align) |
| 74 | [How to improve readability using typography?](#how-to-improve-readability-using-typography) |
| 75 | [What is font loading behaviour?](#what-is-font-loading-behaviour) |
| 76 | [What is font-display?](#what-is-font-display) |
| 77 | [What are variable fonts?](#what-are-variable-fonts) |
| 78 | [How can you make typography responsive?](#how-can-you-make-typography-responsive) |
| 79 | [How do you center text vertically and horizontally?](#how-do-you-center-text-vertically-and-horizontally) |
| 80 | [Explain text-overflow: clip vs. ellipsis.](#explain-text-overflow-clip-vs-ellipsis) |
| 81 | [What is writing-mode?](#what-is-writing-mode) |
| 82 | [What does unicode-bidi do?](#what-does-unicode-bidi-do) |
| 83 | [How do you implement drop caps?](#how-do-you-implement-drop-caps) |
| 84 | [What is text-shadow?](#what-is-text-shadow) |
| 85 | [What is line-clamp and -webkit-line-clamp?](#what-is-line-clamp-and--webkit-line-clamp) |
| 86 | [What is hyphenation?](#what-is-hyphenation) |
| 87 | [How do you use CSS counters for numbered lists?](#how-do-you-use-css-counters-for-numbered-lists) |
| 88 | [What is the overflow-wrap property?](#what-is-the-overflow-wrap-property) |
| 89 | [What is word-break?](#what-is-word-break) |
| 90 | [What is tab-size?](#what-is-tab-size) |
|     | **Display & Visibility** |
| 91 | [What is the display property?](#what-is-the-display-property) |
| 92 | [Difference between block, inline and inline-block?](#difference-between-block-inline-and-inline-block) |
| 93 | [Difference between display: none and visibility: hidden? (revisited)](#difference-between-display-none-and-visibility-hidden-revisited) |
| 94 | [Difference between visibility: hidden and opacity: 0?](#difference-between-visibility-hidden-and-opacity-0) |
| 95 | [Does display: none affect accessibility?](#does-display-none-affect-accessibility) |
| 96 | [What is display: contents? (revisited)](#what-is-display-contents-revisited) |
| 97 | [What is display: flow-root? (revisited)](#what-is-display-flow-root-revisited) |
| 98 | [Describe flex and grid display types.](#describe-flex-and-grid-display-types) |
| 99 | [What is display: inline-flex?](#what-is-display-inline-flex) |
| 100 | [What is the difference between overflow: auto and overflow: scroll?](#what-is-the-difference-between-overflow-auto-and-overflow-scroll) |
| 101 | [When do you need overflow: hidden?](#when-do-you-need-overflow-hidden) |
| 102 | [What is object-fit?](#what-is-object-fit) |
| 103 | [What is object-position?](#what-is-object-position) |
| 104 | [What is visibility: collapse?](#what-is-visibility-collapse) |
| 105 | [What is stacking context?](#what-is-stacking-context) |
| 106 | [What is z-index?](#what-is-z-index) |
| 107 | [When does z-index not work?](#when-does-z-index-not-work) |
| 108 | [What is order in flexbox?](#what-is-order-in-flexbox) |
| 109 | [How does z-index behave with transform?](#how-does-z-index-behave-with-transform) |
| 110 | [How do you center an element vertically in the viewport?](#how-do-you-center-an-element-vertically-in-the-viewport) |
|     | **Positioning** |
| 111 | [What is the difference between position: relative and absolute?](#what-is-the-difference-between-position-relative-and-absolute) |
| 112 | [When do you use position: fixed?](#when-do-you-use-position-fixed) |
| 113 | [How does position: sticky work?](#how-does-position-sticky-work) |
| 114 | [How do you center an absolutely positioned element?](#how-do-you-center-an-absolutely-positioned-element) |
| 115 | [Difference between positioning and transform-based movement?](#difference-between-positioning-and-transform-based-movement) |
| 116 | [What is the difference between float and flex?](#what-is-the-difference-between-float-and-flex) |
| 117 | [What is clear?](#what-is-clear) |
| 118 | [What is position: static?](#what-is-position-static) |
| 119 | [How do you create equal height columns using CSS?](#how-do-you-create-equal-height-columns-using-css) |
| 120 | [What is a containing block?](#what-is-a-containing-block) |
|     | **Flexbox** |
| 121 | [What is flexbox?](#what-is-flexbox) |
| 122 | [What are main axis and cross axis?](#what-are-main-axis-and-cross-axis) |
| 123 | [What is a flex container?](#what-is-a-flex-container) |
| 124 | [What are flex items?](#what-are-flex-items) |
| 125 | [What is flex-direction?](#what-is-flex-direction) |
| 126 | [What does justify-content do?](#what-does-justify-content-do) |
| 127 | [What does align-items do?](#what-does-align-items-do) |
| 128 | [Difference between align-items and align-content?](#difference-between-align-items-and-align-content) |
| 129 | [What is flex-wrap?](#what-is-flex-wrap) |
| 130 | [What does the gap property do in flexbox?](#what-does-the-gap-property-do-in-flexbox) |
| 131 | [Explain flex-grow, flex-shrink, and flex-basis.](#explain-flex-grow-flex-shrink-and-flex-basis) |
| 132 | [What does flex: 1 mean?](#what-does-flex-1-mean) |
| 133 | [What is the default value of flex-shrink?](#what-is-the-default-value-of-flex-shrink) |
| 134 | [How do you center an element using flexbox?](#how-do-you-center-an-element-using-flexbox) |
| 135 | [How do you create equal-width columns with flexbox?](#how-do-you-create-equal-width-columns-with-flexbox) |
| 136 | [How do you reorder flex items?](#how-do-you-reorder-flex-items) |
| 137 | [What is the flex-flow shorthand?](#what-is-the-flex-flow-shorthand) |
| 138 | [Why might flex: 1 0 0 be used instead of flex: 1?](#why-might-flex-1-0-0-be-used-instead-of-flex-1) |
| 139 | [How do you prevent a flex item from shrinking?](#how-do-you-prevent-a-flex-item-from-shrinking) |
| 140 | [What is align-self?](#what-is-align-self) |
| 141 | [What is flex-basis: auto?](#what-is-flex-basis-auto) |
| 142 | [How do you make a vertical flexbox?](#how-do-you-make-a-vertical-flexbox) |
| 143 | [What is flex-wrap: wrap-reverse?](#what-is-flex-wrap-wrap-reverse) |
| 144 | [What is flex-end?](#what-is-flex-end) |
| 145 | [Explain space-between, space-around and space-evenly.](#explain-space-between-space-around-and-space-evenly) |
| 146 | [How do you create responsive navigation with flexbox?](#how-do-you-create-responsive-navigation-with-flexbox) |
| 147 | [What are common flexbox layout issues?](#what-are-common-flexbox-layout-issues) |
| 148 | [When should you use flexbox vs. CSS Grid?](#when-should-you-use-flexbox-vs-css-grid) |
| 149 | [Can flex and grid be used together?](#can-flex-and-grid-be-used-together) |
| 150 | [What does min-content do in flexbox and grid?](#what-does-min-content-do-in-flexbox-and-grid) |
|     | **CSS Grid** |
| 151 | [What is CSS Grid?](#what-is-css-grid) |
| 152 | [Difference between Grid and Flexbox?](#difference-between-grid-and-flexbox) |
| 153 | [What is a grid container?](#what-is-a-grid-container) |
| 154 | [What is a grid item?](#what-is-a-grid-item) |
| 155 | [Explain grid-template-columns.](#explain-grid-template-columns) |
| 156 | [Explain grid-template-rows.](#explain-grid-template-rows) |
| 157 | [What is the fr unit again?](#what-is-the-fr-unit-again) |
| 158 | [What are explicit vs. implicit grids?](#what-are-explicit-vs-implicit-grids) |
| 159 | [What is grid-auto-flow?](#what-is-grid-auto-flow) |
| 160 | [What are grid-auto-rows and grid-auto-columns?](#what-are-grid-auto-rows-and-grid-auto-columns) |
| 161 | [What is the gap property in Grid?](#what-is-the-gap-property-in-grid) |
| 162 | [Explain grid-column and grid-row.](#explain-grid-column-and-grid-row) |
| 163 | [What is grid-area?](#what-is-grid-area) |
| 164 | [What are named grid areas?](#what-are-named-grid-areas) |
| 165 | [What is the repeat() function?](#what-is-the-repeat-function) |
| 166 | [Difference between auto-fill and auto-fit in repeat()?](#difference-between-auto-fill-and-auto-fit-in-repeat) |
| 167 | [What is minmax()?](#what-is-minmax) |
| 168 | [How do you use minmax() for responsive cards?](#how-do-you-use-minmax-for-responsive-cards) |
| 169 | [What is auto in grid tracks?](#what-is-auto-in-grid-tracks) |
| 170 | [What is fit-content()?](#what-is-fit-content) |
| 171 | [How do you center items in a grid cell?](#how-do-you-center-items-in-a-grid-cell) |
| 172 | [What is the subgrid feature?](#what-is-the-subgrid-feature) |
| 173 | [How do you create a masonry layout with CSS Grid?](#how-do-you-create-a-masonry-layout-with-css-grid) |
| 174 | [How do you overlay items using grid?](#how-do-you-overlay-items-using-grid) |
| 175 | [How can you reorder grid items?](#how-can-you-reorder-grid-items) |
| 176 | [What are implicit named lines?](#what-are-implicit-named-lines) |
| 177 | [What does grid-template shorthand do?](#what-does-grid-template-shorthand-do) |
| 178 | [What is place-items?](#what-is-place-items) |
| 179 | [How do you create a CSS grid fallback?](#how-do-you-create-a-css-grid-fallback) |
| 180 | [What is grid-row-gap and grid-column-gap?](#what-is-grid-row-gap-and-grid-column-gap) |
|     | **Responsive Design, Media & Container Queries** |
| 181 | [What is responsive web design?](#what-is-responsive-web-design) |
| 182 | [What are media queries?](#what-are-media-queries) |
| 183 | [What is the syntax of a media query?](#what-is-the-syntax-of-a-media-query) |
| 184 | [Difference between min-width and max-width media queries?](#difference-between-min-width-and-max-width-media-queries) |
| 185 | [What is mobile-first CSS?](#what-is-mobile-first-css) |
| 186 | [What is desktop-first CSS?](#what-is-desktop-first-css) |
| 187 | [What are breakpoints?](#what-are-breakpoints) |
| 188 | [How do you decide breakpoints?](#how-do-you-decide-breakpoints) |
| 189 | [What is a fluid layout?](#what-is-a-fluid-layout) |
| 190 | [What is responsive typography?](#what-is-responsive-typography) |
| 191 | [What is the clamp() function?](#what-is-the-clamp-function) |
| 192 | [How does min() work in CSS?](#how-does-min-work-in-css) |
| 193 | [How does max() work in CSS?](#how-does-max-work-in-css) |
| 194 | [How do you make images responsive?](#how-do-you-make-images-responsive) |
| 195 | [What is object-fit: cover vs. contain again?](#what-is-object-fit-cover-vs-contain-again) |
| 196 | [What is the <picture> element?](#what-is-the-picture-element) |
| 197 | [What are container queries?](#what-are-container-queries) |
| 198 | [How are container queries different from media queries?](#how-are-container-queries-different-from-media-queries) |
| 199 | [Explain container-type property.](#explain-container-type-property) |
| 200 | [How do you write a container query?](#how-do-you-write-a-container-query) |
| 201 | [What is prefers-color-scheme?](#what-is-prefers-color-scheme) |
| 202 | [What is prefers-reduced-motion?](#what-is-prefers-reduced-motion) |
| 203 | [What is pointer and hover in media queries?](#what-is-pointer-and-hover-in-media-queries) |
| 204 | [What is aspect-ratio in CSS?](#what-is-aspect-ratio-in-css) |
| 205 | [How do you build accessible responsive tables?](#how-do-you-build-accessible-responsive-tables) |
| 206 | [What is @supports rule?](#what-is-supports-rule) |
| 207 | [What is calc()?](#what-is-calc) |
| 208 | [How can you prevent horizontal overflow on small screens?](#how-can-you-prevent-horizontal-overflow-on-small-screens) |
| 209 | [What are logical properties?](#what-are-logical-properties) |
| 210 | [What is the difference between vh and svh / lvh / dvh?](#what-is-the-difference-between-vh-and-svh--lvh--dvh) |
|     | **Pseudo-classes, Pseudo-elements & Selectors** |
| 211 | [What is :hover?](#what-is-hover) |
| 212 | [What is :focus and :focus-visible?](#what-is-focus-and-focus-visible) |
| 213 | [What is :active?](#what-is-active) |
| 214 | [What is :visited?](#what-is-visited) |
| 215 | [What is :first-child and :last-child?](#what-is-first-child-and-last-child) |
| 216 | [What is :nth-child(n)?](#what-is-nth-childn) |
| 217 | [Difference between :nth-child() and :nth-of-type() again?](#difference-between-nth-child-and-nth-of-type-again) |
| 218 | [What is :not()?](#what-is-not) |
| 219 | [What is :is()?](#what-is-is) |
| 220 | [What is :where()?](#what-is-where) |
| 221 | [What is :has()?](#what-is-has) |
| 222 | [What are pseudo-elements like ::before and ::after?](#what-are-pseudo-elements-like-before-and-after) |
| 223 | [What is ::first-line?](#what-is-first-line) |
| 224 | [What is ::placeholder?](#what-is-placeholder) |
| 225 | [What is ::selection?](#what-is-selection) |
| 226 | [How can you chain pseudo-classes?](#how-can-you-chain-pseudo-classes) |
| 227 | [What is specificity of pseudo-classes?](#what-is-specificity-of-pseudo-classes) |
| 228 | [What is the difference between single and double colon syntax?](#what-is-the-difference-between-single-and-double-colon-syntax) |
| 229 | [Why does :visited have restrictions?](#why-does-visited-have-restrictions) |
| 230 | [What is the difference between ::after and :after?](#what-is-the-difference-between-after-and-after) |
|     | **Transitions, Animations, Transforms, Performance & Architecture** |
| 231 | [What is a CSS transition?](#what-is-a-css-transition) |
| 232 | [Which properties can be transitioned?](#which-properties-can-be-transitioned) |
| 233 | [What is transition-property?](#what-is-transition-property) |
| 234 | [What is transition-duration?](#what-is-transition-duration) |
| 235 | [What is transition-delay?](#what-is-transition-delay) |
| 236 | [What is transition-timing-function?](#what-is-transition-timing-function) |
| 237 | [What is a CSS animation?](#what-is-a-css-animation) |
| 238 | [What is @keyframes?](#what-is-keyframes) |
| 239 | [What is animation-name?](#what-is-animation-name) |
| 240 | [What is animation-duration?](#what-is-animation-duration) |
| 241 | [What is animation-fill-mode?](#what-is-animation-fill-mode) |
| 242 | [What is animation-direction?](#what-is-animation-direction) |
| 243 | [What is animation-iteration-count?](#what-is-animation-iteration-count) |
| 244 | [What is animation-play-state?](#what-is-animation-play-state) |
| 245 | [What does transform do?](#what-does-transform-do) |
| 246 | [Difference between translate, scale, rotate and skew?](#difference-between-translate-scale-rotate-and-skew) |
| 247 | [Why is transform better than changing top/left for animation?](#why-is-transform-better-than-changing-topleft-for-animation) |
| 248 | [What is will-change?](#what-is-will-change) |
| 249 | [How do you respect reduced motion preferences?](#how-do-you-respect-reduced-motion-preferences) |
| 250 | [What are CSS architecture methodologies?](#what-are-css-architecture-methodologies) |

</details>

---

## Fundamentals & Selectors

1. ### What is CSS and why is it used?

   **CSS (Cascading Style Sheets)** describes how HTML elements are rendered on screen, paper, or other media. Its core purpose is to **separate content (HTML) from presentation (styling)**, which enables consistent styling across many pages, reduces duplication, and makes maintenance far easier. Because styles *cascade*, declarations from external, internal, and inline sources combine — along with specificity and source order — to compute the final value for every property on every element.

   ```css
   /* One rule styles every paragraph site-wide */
   p {
     color: #333;
     line-height: 1.6;
     margin-block: 1rem;
   }
   ```

   **Key benefits:** separation of concerns, reusability, smaller HTML, browser caching of external files, responsive design, and accessibility (users can override styles).

   **[⬆ Back to Top](#table-of-contents)**

2. ### How do you include CSS in a page?

   There are three ways to apply CSS, in increasing order of maintainability:

   | Method | Example | When to use |
   | --- | --- | --- |
   | **Inline** | `<p style="color:red">` | Rare; quick overrides, email HTML |
   | **Internal** | `<style>` block in `<head>` | Single-page documents, demos |
   | **External** | `<link rel="stylesheet" href="styles.css">` | **Preferred** — caching, reuse, separation |

   ```html
   <!-- Inline -->
   <p style="color: red;">Inline styled text</p>

   <!-- Internal -->
   <head>
     <style>
       p { color: blue; }
     </style>
   </head>

   <!-- External (preferred) -->
   <head>
     <link rel="stylesheet" href="styles.css">
   </head>
   ```

   External stylesheets are preferred because the browser caches them across pages and they keep styling separate from markup.

   **[⬆ Back to Top](#table-of-contents)**

3. ### What is the CSS cascade?

   The **cascade** is the algorithm the browser uses to resolve conflicts when multiple declarations target the same property on the same element. It sorts declarations in this order of precedence:

   1. **Origin and importance** — user-agent < user < author styles; `!important` flips the order within these.
   2. **Specificity** — a more specific selector wins (see next question).
   3. **Source order** — when specificity ties, the **last** declaration wins.

   ```css
   p { color: black; }          /* specificity 0-0-1 */
   .intro { color: blue; }      /* specificity 0-1-0 → wins over the type selector */
   #lead { color: green; }      /* specificity 1-0-0 → wins over the class */
   ```

   For `<p id="lead" class="intro">`, the text is **green** because the ID selector has the highest specificity.

   **[⬆ Back to Top](#table-of-contents)**

4. ### Explain selector specificity.

   **Specificity** is a three-part score `(IDs, Classes, Types)` that determines which rule wins when declarations conflict:

   | Selector component | Weight | Example |
   | --- | --- | --- |
   | Inline style | 1-0-0-0 | `style="..."` |
   | ID | 0-1-0-0 | `#header` |
   | Class, attribute, pseudo-class | 0-0-1-0 | `.btn`, `[type]`, `:hover` |
   | Type, pseudo-element | 0-0-0-1 | `div`, `::before` |
   | Universal `*`, combinators | 0 | `*`, `>`, `+`, `~` |

   ```css
   /* 0-0-1-1 */  nav a { color: gray; }
   /* 0-1-0-0 */  #cta   { color: red; }   /* wins — one ID beats any number of classes/types */
   ```

   A single ID (0-1-0-0) outranks even many classes (e.g. 0-0-5-0). When two selectors have **equal** specificity, the later one wins. `!important` and inline styles sit above the normal calculation.

   **[⬆ Back to Top](#table-of-contents)**

5. ### Difference between id, class and element selectors?

   | Selector | Syntax | Matches | Specificity | Reusable? |
   | --- | --- | --- | --- | --- |
   | **ID** | `#header` | One unique element (`id` is unique per page) | High (0-1-0-0) | No |
   | **Class** | `.highlight` | Any number of elements | Medium (0-0-1-0) | Yes |
   | **Element** | `p` | All elements of that type | Low (0-0-0-1) | Yes |

   ```css
   #main-nav  { background: navy; }   /* the single nav with id="main-nav" */
   .card      { border: 1px solid; }  /* every element with class="card" */
   a          { text-decoration: none; } /* all anchors */
   ```

   **Best practice:** style with classes for flexibility; reserve IDs for unique landmarks or JS/anchor hooks.

   **[⬆ Back to Top](#table-of-contents)**

6. ### What is the universal selector?

   The **universal selector** `*` matches **every element**. It has **zero specificity**, so it never wins specificity battles. It is commonly used for resets:

   ```css
   /* Apply border-box sizing to everything, including pseudo-elements */
   *, *::before, *::after {
     box-sizing: border-box;
     margin: 0;
     padding: 0;
   }
   ```

   It can also be combined in selectors (e.g., `.menu > *` targets all direct children). Use it deliberately — applying expensive properties to every node can affect performance on huge DOMs.

   **[⬆ Back to Top](#table-of-contents)**

7. ### What are grouping selectors?

   **Grouping** combines multiple selectors separated by commas so they share one declaration block. This avoids repetition (DRY):

   ```css
   /* Instead of three separate rules */
   h1, h2, h3 {
     color: navy;
     font-family: Georgia, serif;
   }
   ```

   Each selector in the group is evaluated independently — a syntax error in one (in older browsers) could invalidate the whole group, though modern parsers and `:is()` mitigate this.

   **[⬆ Back to Top](#table-of-contents)**

8. ### Describe descendant selectors.

   A **descendant selector** (space combinator) targets an element nested **anywhere** inside an ancestor, at any depth:

   ```css
   /* Every <p> inside .card, no matter how deeply nested */
   .card p {
     margin-bottom: 0.5rem;
   }
   ```

   ```html
   <div class="card">
     <p>Matched</p>
     <div><p>Also matched (deeper)</p></div>
   </div>
   ```

   Because it matches at any depth, it can be less predictable than the child combinator; keep selectors shallow for performance and clarity.

   **[⬆ Back to Top](#table-of-contents)**

9. ### Difference between child and descendant selectors?

   | Combinator | Symbol | Matches |
   | --- | --- | --- |
   | **Descendant** | space (` `) | Any nested descendant at any depth |
   | **Child** | `>` | Only **direct** children (one level) |

   ```css
   .menu li      { color: gray; }  /* every li inside .menu, including nested submenus */
   .menu > li    { font-weight: bold; } /* only top-level li children of .menu */
   ```

   ```html
   <ul class="menu">
     <li>Top level — bold + gray</li>
     <li>Top level
       <ul><li>Nested — gray only (not bold)</li></ul>
     </li>
   </ul>
   ```

   **[⬆ Back to Top](#table-of-contents)**

10. ### Adjacent sibling vs. general sibling selectors?

    Both target siblings (elements sharing the same parent), but differ in scope:

    | Selector | Symbol | Matches |
    | --- | --- | --- |
    | **Adjacent sibling** | `A + B` | The **single** `B` immediately following `A` |
    | **General sibling** | `A ~ B` | **All** `B` siblings that come after `A` |

    ```css
    h2 + p  { margin-top: 0; }      /* only the first paragraph right after an h2 */
    h2 ~ p  { color: #666; }        /* every paragraph after an h2 (same parent) */
    ```

    Neither selects siblings that come *before* `A`, and both require the elements to share a parent.

    **[⬆ Back to Top](#table-of-contents)**

11. ### What are attribute selectors?

    **Attribute selectors** match elements based on the presence or value of an attribute:

    | Selector | Matches |
    | --- | --- |
    | `[disabled]` | Elements with the attribute (any value) |
    | `[type="email"]` | Exact value match |
    | `[class~="btn"]` | Whitespace-separated list containing the word |
    | `[lang|="en"]` | Exactly `en` or starting with `en-` |
    | `[href^="https"]` | Value **starts with** |
    | `[href$=".pdf"]` | Value **ends with** |
    | `[href*="example"]` | Value **contains** substring |

    ```css
    input[type="email"]      { border: 1px solid blue; }
    a[href^="https"]::after  { content: " 🔒"; }   /* secure links */
    a[href$=".pdf"]          { color: crimson; }    /* PDF links */
    [data-role^="nav"]       { font-weight: bold; } /* data-role starting with "nav" */
    ```

    Add `i` before the closing bracket for case-insensitive matching: `[type="EMAIL" i]`.

    **[⬆ Back to Top](#table-of-contents)**

12. ### What does !important do?

    Appending `!important` to a declaration raises it above the normal cascade — it overrides any non-important declaration regardless of specificity or source order:

    ```css
    .alert { color: red !important; }  /* beats even #id selectors that aren't !important */
    ```

    **Conflict rules:** when two `!important` declarations clash, normal specificity and source order decide between them. **Use sparingly** — it breaks the natural cascade, makes debugging hard, and the only way to override it is another `!important` with higher specificity. Legitimate uses include utility classes and overriding third-party styles you cannot edit.

    **[⬆ Back to Top](#table-of-contents)**

13. ### Which properties are inherited by default?

    Some properties pass their computed value to descendants automatically; most do not.

    | Inherited (mostly typography) | Not inherited (mostly layout/box) |
    | --- | --- |
    | `color`, `font-*`, `line-height` | `width`, `height`, `margin`, `padding` |
    | `letter-spacing`, `word-spacing` | `border`, `background` |
    | `text-align`, `text-indent` | `display`, `position`, `float` |
    | `visibility`, `cursor`, `list-style` | `top`/`right`/`bottom`/`left`, `z-index` |

    You can force behavior with the `inherit`, `initial`, `unset`, and `revert` keywords:

    ```css
    .box { border: inherit; }   /* explicitly take the parent's border */
    a    { color: inherit; }    /* make links use surrounding text color */
    ```

    **[⬆ Back to Top](#table-of-contents)**

14. ### What is the default user agent stylesheet?

    Every browser ships a **user-agent (UA) stylesheet** that provides baseline styling so unstyled HTML is still usable: margins on headings and paragraphs, bullets on `<ul>`, underlined blue links, bold `<strong>`, etc. Because these defaults differ slightly between browsers, developers apply a **reset** (e.g., Eric Meyer's reset, which zeroes everything) or a **normalize** (normalize.css, which makes defaults consistent while preserving useful ones):

    ```css
    /* Tiny modern reset */
    *, *::before, *::after { box-sizing: border-box; }
    body, h1, h2, p, figure { margin: 0; }
    ul[role="list"] { list-style: none; padding: 0; }
    ```

    **[⬆ Back to Top](#table-of-contents)**

15. ### What is the difference between inline, internal and external CSS?

    | Type | Where it lives | Specificity impact | Pros | Cons |
    | --- | --- | --- | --- | --- |
    | **Inline** | `style` attribute on the element | Very high (1-0-0-0) | Quick, scoped to one element | Not reusable, no caching, mixes content & style |
    | **Internal** | `<style>` in `<head>` | Normal | No extra request, page-scoped | Not shared across pages |
    | **External** | Separate `.css` file via `<link>` | Normal | Cached, reusable, clean separation | Extra HTTP request (mitigated by caching) |

    **External CSS** is the standard for production: one cached file styles an entire site, improving load time and maintainability.

    **[⬆ Back to Top](#table-of-contents)**

16. ### Explain the :root pseudo-class.

    `:root` matches the document's root element — `<html>` in HTML — but with **higher specificity** than the `html` type selector (it counts as a class: 0-0-1-0). Its primary use is declaring **global CSS custom properties (variables)**:

    ```css
    :root {
      --brand: #4f46e5;
      --gap: 1rem;
      --radius: 8px;
    }

    .button {
      background: var(--brand);
      padding: var(--gap);
      border-radius: var(--radius);
    }
    ```

    Defining variables on `:root` makes them available everywhere in the document, and they can be overridden in narrower scopes or media queries (e.g., dark mode).

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is a combinator?

    A **combinator** expresses a relationship between two selectors. CSS has these:

    | Combinator | Symbol | Relationship |
    | --- | --- | --- |
    | Descendant | (space) | B nested anywhere inside A |
    | Child | `>` | B is a direct child of A |
    | Adjacent sibling | `+` | B immediately follows A |
    | General sibling | `~` | B follows A (same parent) |

    ```css
    article > h2 + p   { font-size: 1.1rem; }
    /* a <p> immediately after an <h2> that is a direct child of <article> */
    ```

    The newer `:has()` relational pseudo-class effectively adds "parent/previous" power that combinators alone never had.

    **[⬆ Back to Top](#table-of-contents)**

18. ### What is the difference between :nth-child() and :nth-of-type()?

    Both accept formulas like `2n` (even), `2n+1` / `odd`, and `n+3` (third onward), but they count differently:

    - **`:nth-child(n)`** counts **all** sibling elements regardless of type, then checks if the matched element is the right *type*.
    - **`:nth-of-type(n)`** counts only siblings **of the same element type**.

    ```css
    li:nth-child(2)   { color: red; }   /* the 2nd child IF it is an <li> */
    li:nth-of-type(2) { color: blue; }  /* the 2nd <li> among its siblings */
    ```

    ```html
    <div>
      <h3>Heading</h3>   <!-- child #1 -->
      <li>First li</li>  <!-- child #2, li-of-type #1 -->
      <li>Second li</li> <!-- child #3, li-of-type #2 -->
    </div>
    <!-- :nth-child(2) matches "First li"; :nth-of-type(2) matches "Second li" -->
    ```

    **[⬆ Back to Top](#table-of-contents)**

19. ### What are pseudo-classes?

    **Pseudo-classes** select elements based on **state or position** that isn't expressible with simple selectors — user interaction, structural position, or form/link state. They use a single colon:

    ```css
    a:hover           { text-decoration: underline; }  /* mouse over */
    input:focus       { outline: 2px solid blue; }     /* focused */
    li:first-child    { font-weight: bold; }            /* structural */
    input:checked     { accent-color: green; }          /* form state */
    button:disabled   { opacity: 0.5; }                 /* UI state */
    ```

    Common groups: **dynamic** (`:hover`, `:active`, `:focus`, `:visited`), **structural** (`:first-child`, `:nth-child`, `:only-child`), **form** (`:checked`, `:disabled`, `:valid`, `:required`), and **functional** (`:not()`, `:is()`, `:where()`, `:has()`).

    **[⬆ Back to Top](#table-of-contents)**

20. ### What are pseudo-elements?

    **Pseudo-elements** style a **specific part** of an element or insert generated content. They use a **double colon** (`::`) to distinguish them from pseudo-classes:

    ```css
    p::first-line   { font-weight: bold; }
    p::first-letter { font-size: 2em; float: left; }
    .quote::before  { content: "“"; }
    .quote::after   { content: "”"; }
    input::placeholder { color: #999; }
    ::selection     { background: yellow; }
    ```

    `::before` and `::after` require the `content` property (even if empty: `content: ""`) to render, and they become child boxes of the element. They cannot be added to replaced elements like `<img>`.

    **[⬆ Back to Top](#table-of-contents)**


## Box Model & Layout

21. ### Explain the CSS box model.

    Every element is a rectangular box composed of four concentric layers, from inside out:

    | Layer | Description |
    | --- | --- |
    | **Content** | The text/image; sized by `width`/`height` |
    | **Padding** | Transparent space inside the border (shows background) |
    | **Border** | Line around the padding |
    | **Margin** | Transparent space outside the border, separating neighbors |

    ```css
    .box {
      width: 200px;       /* content width (in content-box) */
      padding: 20px;      /* inside the border */
      border: 4px solid;  /* around the padding */
      margin: 16px;       /* outside the border */
    }
    /* In content-box, total rendered width = 200 + 20*2 + 4*2 = 248px (margin adds external space) */
    ```

    Understanding which layers `width` includes is the source of most layout surprises — controlled by `box-sizing`.

    **[⬆ Back to Top](#table-of-contents)**

22. ### Difference between padding and margin?

    | | Padding | Margin |
    | --- | --- | --- |
    | **Location** | Inside the border | Outside the border |
    | **Background** | Shows the element's background | Transparent |
    | **Collapsing** | Never collapses | Vertical margins collapse |
    | **Click area** | Part of the element (clickable) | Not part of the element |
    | **Negative values** | Not allowed | Allowed (`margin: -10px`) |

    ```css
    .btn {
      padding: 12px 24px;  /* grows the clickable area, inside background */
      margin: 8px;         /* space between this button and others */
    }
    ```

    Rule of thumb: use **padding** to create space *within* a component and **margin** to create space *between* components.

    **[⬆ Back to Top](#table-of-contents)**

23. ### What is margin collapsing?

    **Margin collapsing** is when two **vertical** margins that meet combine into a single margin equal to the **larger** of the two (not their sum). It happens in three cases: between adjacent siblings, between a parent and its first/last child, and within empty blocks.

    ```css
    .a { margin-bottom: 30px; }
    .b { margin-top: 20px; }
    /* The gap between .a and .b is 30px (the larger), NOT 50px */
    ```

    Collapsing only affects **block-level vertical** margins in normal flow. Horizontal margins, and margins inside flex/grid containers, never collapse.

    **[⬆ Back to Top](#table-of-contents)**

24. ### How can you prevent margin collapsing?

    Establish a boundary between the margins. Any of these stop collapse:

    ```css
    /* 1. Add padding or border to the parent */
    .parent { padding-top: 1px; }

    /* 2. Create a Block Formatting Context */
    .parent { overflow: auto; }      /* or hidden */
    .parent { display: flow-root; }  /* cleanest — no side effects */

    /* 3. Use flex/grid — they never collapse margins */
    .parent { display: flex; flex-direction: column; }
    ```

    `display: flow-root` is the modern, side-effect-free choice for creating the formatting context that blocks collapsing.

    **[⬆ Back to Top](#table-of-contents)**

25. ### Explain box-sizing.

    `box-sizing` controls whether `width`/`height` refer to just the content box or include padding and border:

    | Value | `width` includes |
    | --- | --- |
    | `content-box` (default) | Content only; padding & border are **added** on top |
    | `border-box` | Content + padding + border (margin still external) |

    ```css
    .content-box { box-sizing: content-box; width: 200px; padding: 20px; border: 5px solid; }
    /* Rendered width = 200 + 40 + 10 = 250px */

    .border-box  { box-sizing: border-box;  width: 200px; padding: 20px; border: 5px solid; }
    /* Rendered width = 200px exactly; content shrinks to 150px */
    ```

    `border-box` makes sizing predictable, which is why most projects set it globally.

    **[⬆ Back to Top](#table-of-contents)**

26. ### Why is box-sizing: border-box preferred?

    With `border-box`, an element's declared `width` is its **actual** rendered width — adding padding or borders shrinks the content area instead of expanding the box. This prevents layouts from breaking when you tweak padding, and makes percentage widths combine cleanly with pixel padding.

    ```css
    /* The near-universal global default */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    .col { width: 50%; padding: 1rem; }  /* still exactly 50% wide — no overflow */
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### Difference between min-width, width, and max-width?

    These three properties constrain an element's width together; the resolution order is `max-width` → `min-width` → `width`:

    | Property | Effect |
    | --- | --- |
    | `width` | Preferred/target width |
    | `min-width` | Floor — element never shrinks below this |
    | `max-width` | Ceiling — element never grows beyond this |

    ```css
    .card {
      width: 100%;       /* try to fill the container */
      max-width: 600px;  /* but never wider than 600px (great for readability) */
      min-width: 280px;  /* and never narrower than 280px */
    }
    ```

    `min-width` wins over `max-width` if they conflict. This trio is the backbone of fluid-yet-bounded responsive components.

    **[⬆ Back to Top](#table-of-contents)**

28. ### How do overflow values differ?

    `overflow` controls what happens when content exceeds its box:

    | Value | Behavior |
    | --- | --- |
    | `visible` (default) | Overflow spills out and is visible |
    | `hidden` | Overflow is clipped and invisible |
    | `scroll` | Always shows scrollbars (even if not needed) |
    | `auto` | Scrollbars appear **only when needed** |
    | `clip` | Like hidden but forbids all scrolling (even programmatic) |

    ```css
    .panel { overflow: auto; }            /* both axes */
    .row   { overflow-x: auto; overflow-y: hidden; } /* per-axis control */
    ```

    Setting `overflow` to anything other than `visible` also creates a new block formatting context (useful for containing floats).

    **[⬆ Back to Top](#table-of-contents)**

29. ### How to create a scrollable container?

    Constrain the height and let overflow scroll:

    ```css
    .scroll-box {
      max-height: 200px;
      overflow-y: auto;          /* vertical scrollbar only when needed */
      overscroll-behavior: contain; /* stop scroll chaining to the page */
    }
    ```

    For horizontal scrolling (e.g., a card carousel), use `overflow-x: auto` with `white-space: nowrap` or a flex row. Add `scroll-behavior: smooth` for animated jumps and `scroll-snap-type` for snapping.

    **[⬆ Back to Top](#table-of-contents)**

30. ### Does outline affect layout?

    **No.** `outline` is drawn **outside** the border edge and does **not** occupy space or shift surrounding elements — it overlaps adjacent content if large. This makes it ideal for focus indicators because toggling it never causes layout shift:

    ```css
    button:focus-visible {
      outline: 2px solid blue;
      outline-offset: 2px;   /* push the outline away from the border */
    }
    ```

    Unlike `border`, outlines can be non-rectangular and don't support per-side control. Never remove focus outlines without providing an alternative — it harms keyboard accessibility.

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is percentage width?

    A percentage `width` is resolved **relative to the width of the containing block** (usually the parent's content width):

    ```css
    .parent { width: 600px; }
    .child  { width: 50%; }   /* = 300px */
    ```

    Note that percentage **padding and margin** (even vertical ones) are also calculated against the containing block's **width**, not height — a common source of confusion. Percentage `height` behaves differently (see Q46).

    **[⬆ Back to Top](#table-of-contents)**

32. ### What happens when content overflows its container?

    By default (`overflow: visible`), content that exceeds the box's dimensions **spills out and remains visible**, potentially overlapping other elements but not affecting their layout. To control this, set `overflow` to clip the content (`hidden`/`clip`) or make it scrollable (`auto`/`scroll`):

    ```css
    .fixed-height {
      height: 100px;
      overflow: auto;  /* contain the overflow with a scrollbar */
    }
    ```

    Overflow commonly occurs with fixed heights, long unbroken words, or large images — `min-width: 0` on flex items and `overflow-wrap` often help.

    **[⬆ Back to Top](#table-of-contents)**

33. ### Difference between margin shorthand and individual sides?

    The `margin` shorthand sets all four sides in a clockwise order from the top:

    | Values given | Interpretation |
    | --- | --- |
    | `margin: 10px` | All four sides |
    | `margin: 10px 20px` | Vertical (top/bottom) `10px`, horizontal (left/right) `20px` |
    | `margin: 10px 20px 30px` | top `10`, horizontal `20`, bottom `30` |
    | `margin: 10px 20px 30px 40px` | top, right, bottom, left (clockwise) |

    ```css
    .a { margin: 1em 2em; }              /* shorthand */
    .b { margin-top: 1em; margin-right: 2em;
         margin-bottom: 1em; margin-left: 2em; } /* equivalent longhand */
    ```

    Logical equivalents (`margin-block`, `margin-inline`) adapt to writing direction.

    **[⬆ Back to Top](#table-of-contents)**

34. ### When does margin collapsing happen?

    Vertical margins collapse in exactly three situations, and **only** in normal block flow:

    1. **Adjacent siblings** — the bottom margin of one and top margin of the next.
    2. **Parent and first/last child** — if no padding, border, or content separates them.
    3. **Empty blocks** — an element's own top and bottom margins collapse if it has no height, padding, border, or content.

    Collapsing does **not** happen for: horizontal margins, floated elements, absolutely positioned elements, flex/grid items, or elements establishing a new block formatting context.

    **[⬆ Back to Top](#table-of-contents)**

35. ### How do you center a block element horizontally?

    The classic method: give it a width and set left/right margins to `auto`:

    ```css
    .container {
      width: 80%;
      max-width: 960px;
      margin-inline: auto;   /* modern logical equivalent of margin: 0 auto */
    }
    ```

    Modern alternatives are often simpler:

    ```css
    /* Flexbox */
    .parent { display: flex; justify-content: center; }
    /* Grid */
    .parent { display: grid; place-items: center; }
    ```

    `margin: auto` only works horizontally for in-flow block elements with a defined width; flex/grid extend `auto` margins to both axes.

    **[⬆ Back to Top](#table-of-contents)**

36. ### What is clearfix?

    A **clearfix** forces a parent to contain its floated children (floats are removed from normal flow, so the parent collapses to zero height without it). The classic technique uses a pseudo-element:

    ```css
    .clearfix::after {
      content: "";
      display: table;   /* or block */
      clear: both;
    }
    ```

    ```html
    <div class="clearfix">
      <div style="float: left">Floated</div>
      <!-- parent now wraps around the float -->
    </div>
    ```

    In modern CSS, `display: flow-root` on the parent achieves the same containment with one line and no pseudo-element — and floats are rarely used for layout now that flex/grid exist.

    **[⬆ Back to Top](#table-of-contents)**

37. ### Difference between display: none and visibility: hidden?

    | | `display: none` | `visibility: hidden` |
    | --- | --- | --- |
    | **Layout space** | Removed entirely (collapses) | Reserved (still occupies space) |
    | **Screen readers** | Not announced | Not announced |
    | **Children** | All hidden | Can re-show a child with `visibility: visible` |
    | **Transitions** | Not animatable | Animatable (it's a discrete change but pairs with opacity) |

    ```css
    .gone   { display: none; }        /* element vanishes, layout reflows */
    .hidden { visibility: hidden; }   /* element invisible but its box remains */
    ```

    Use `display: none` to remove an element from the flow; `visibility: hidden` to hide it while preserving its footprint.

    **[⬆ Back to Top](#table-of-contents)**

38. ### Describe display: contents.

    `display: contents` makes an element's **own box disappear** while keeping its children in the layout — the children behave as if they were direct children of the grandparent. This is useful for promoting children into a flex/grid container through a wrapper:

    ```css
    .grid { display: grid; grid-template-columns: repeat(3, 1fr); }
    .wrapper { display: contents; }  /* its children become grid items directly */
    ```

    ```html
    <div class="grid">
      <div class="wrapper"><div>A</div><div>B</div><div>C</div></div>
      <!-- A, B, C participate in the grid directly -->
    </div>
    ```

    **Accessibility caveat:** historically some browsers removed the element's semantics; verify with assistive tech before using on semantic elements.

    **[⬆ Back to Top](#table-of-contents)**

39. ### What is display: flow-root?

    `display: flow-root` creates a **new block formatting context (BFC)** with no side effects. A BFC contains floats and prevents margin collapsing between the element and its children — solving the same problems as clearfix or `overflow: hidden`, but without clipping content or hacks:

    ```css
    .container {
      display: flow-root;  /* contains floated children, blocks margin collapse */
    }
    ```

    It's the cleanest, purpose-built solution introduced specifically to replace the old `overflow: hidden` and clearfix workarounds.

    **[⬆ Back to Top](#table-of-contents)**

40. ### Can inline elements have width/height?

    **No.** Pure inline elements (`<span>`, `<a>`, `<em>`) ignore `width` and `height`, and their vertical margins/padding don't push surrounding content (though horizontal ones do). To give them dimensions, change their display type:

    ```css
    .badge {
      display: inline-block;  /* flows inline but accepts width/height */
      width: 60px;
      height: 24px;
    }
    ```

    Options: `inline-block` (sized box that flows in text), `block` (full-width box), or making the parent a flex/grid container (which gives items block-like sizing).

    **[⬆ Back to Top](#table-of-contents)**


## Units & Colors

41. ### Absolute vs. relative units?

    | Type | Units | Relative to |
    | --- | --- | --- |
    | **Absolute** | `px`, `pt`, `cm`, `mm`, `in`, `pc` | Fixed physical/device size |
    | **Relative** | `%`, `em`, `rem`, `vw`, `vh`, `vmin`, `vmax`, `ch`, `ex`, `svh`/`lvh`/`dvh` | Font size, viewport, or parent |

    ```css
    .fixed { width: 200px; }      /* always 200 device pixels */
    .fluid { width: 50%;  }       /* half of containing block */
    .scaled { font-size: 1.25rem; } /* 1.25 × root font size */
    ```

    Relative units are preferred for responsive, accessible layouts because they scale with user settings and viewport size. `px` remains useful for borders and hairline details.

    **[⬆ Back to Top](#table-of-contents)**

42. ### Difference between px, %, em and rem?

    | Unit | Relative to | Compounds? |
    | --- | --- | --- |
    | `px` | Nothing (device pixel) | No |
    | `%` | Parent's corresponding dimension | Yes |
    | `em` | The element's own `font-size` (or parent's for `font-size` itself) | Yes (nests) |
    | `rem` | The root (`<html>`) `font-size` | No |

    ```css
    html { font-size: 16px; }
    .a { font-size: 1.5em; }   /* 24px if parent is 16px */
    .a .b { font-size: 1.5em; } /* 36px — compounds off .a! */
    .c { font-size: 1.5rem; }  /* always 24px, no compounding */
    ```

    `rem` is favored for predictable typography; `em` shines for component-internal spacing that should scale with the component's own text.

    **[⬆ Back to Top](#table-of-contents)**

43. ### Difference between em and rem when used on font-size?

    On `font-size`, `em` references the **parent element's** font size and therefore **compounds** through nesting, while `rem` always references the **root** font size and stays stable:

    ```css
    html { font-size: 16px; }
    ul { font-size: 0.9em; }   /* nested lists shrink each level: 14.4px, 12.96px... */
    ul { font-size: 0.9rem; }  /* every level is 14.4px — no compounding */
    ```

    Use `rem` when you want consistency regardless of depth; use `em` deliberately when you *want* nested scaling (e.g., progressively smaller nested menus).

    **[⬆ Back to Top](#table-of-contents)**

44. ### What are viewport units?

    Viewport units are percentages of the browser viewport:

    | Unit | Equals |
    | --- | --- |
    | `vw` | 1% of viewport **width** |
    | `vh` | 1% of viewport **height** |
    | `vmin` | 1% of the **smaller** dimension |
    | `vmax` | 1% of the **larger** dimension |
    | `svh` / `lvh` / `dvh` | Small / large / **dynamic** viewport height (handles mobile UI bars) |

    ```css
    .hero { height: 100vh; }       /* full screen height */
    .modal { width: 90vw; max-width: 500px; }
    .fluid-title { font-size: 5vw; } /* scales with screen width */
    ```

    The newer `dvh` is especially useful on mobile, where browser chrome (address bars) changes the usable height dynamically.

    **[⬆ Back to Top](#table-of-contents)**

45. ### When should you use rem instead of px?

    Use `rem` for **typography, spacing, and component sizing** that should respect the user's browser font-size preference — critical for accessibility. A user who sets a larger default font sees your whole layout scale proportionally:

    ```css
    html { font-size: 100%; }  /* respects user's 16px default */
    h1 { font-size: 2rem; }    /* 32px now, but scales if user increases base */
    .card { padding: 1.5rem; gap: 1rem; }
    ```

    Reserve `px` for things that should **not** scale: 1px borders, box shadows, and precise hairline details. This `rem`-for-scale, `px`-for-detail split is a common, robust convention.

    **[⬆ Back to Top](#table-of-contents)**

46. ### How does percentage height work?

    A percentage `height` resolves against the **containing block's height** — but only if that parent has an **explicitly defined height**. If the parent's height is `auto` (content-based), a percentage height has nothing to resolve against and falls back to `auto`:

    ```css
    .parent { height: 400px; }
    .child  { height: 50%; }   /* = 200px ✓ */

    .parent-auto { /* no height set */ }
    .child2 { height: 50%; }   /* behaves like auto — ignored ✗ */
    ```

    Workarounds: set a height on the ancestor chain (`html, body { height: 100% }`), or use viewport units / flex / grid, which size children without this constraint.

    **[⬆ Back to Top](#table-of-contents)**

47. ### What is the ch unit?

    The `ch` unit equals the advance width of the **"0" (zero) glyph** in the element's current font. It's ideal for sizing based on character count — most famously for limiting line length to an optimal reading measure:

    ```css
    .prose {
      max-width: 65ch;  /* ~65 characters per line — great readability */
    }
    input { width: 20ch; }  /* roughly fits a 20-character entry */
    ```

    Because it depends on the font, `ch` is approximate for proportional fonts (where glyphs vary in width) but precise for monospace fonts.

    **[⬆ Back to Top](#table-of-contents)**

48. ### What is the ex unit?

    The `ex` unit equals the **x-height** of the current font — the height of the lowercase "x". It's rarely used because x-heights vary widely between fonts and are hard to predict, but it can fine-tune vertical alignment of inline elements relative to text:

    ```css
    sup { vertical-align: 0.5ex; }  /* nudge superscript relative to x-height */
    ```

    In practice, `rem`, `em`, and `ch` cover most needs; `ex` is a niche typographic tool.

    **[⬆ Back to Top](#table-of-contents)**

49. ### What is the fr unit in CSS Grid?

    `fr` ("fraction") represents a share of the **remaining free space** in a grid container after fixed-size tracks and gaps are subtracted:

    ```css
    .grid {
      display: grid;
      grid-template-columns: 1fr 2fr 1fr;  /* 25% / 50% / 25% of free space */
    }

    .sidebar-layout {
      grid-template-columns: 250px 1fr;  /* fixed sidebar, content fills the rest */
    }
    ```

    `fr` distributes space proportionally and accounts for `gap`, making it cleaner than percentages (which don't subtract gaps). Combine with `minmax()` for flexible-but-bounded tracks.

    **[⬆ Back to Top](#table-of-contents)**

50. ### How do CSS custom units differ from CSS variables?

    CSS has **no mechanism to define new units**. What people sometimes call "custom units" are actually **custom properties (variables)** holding a value that includes a unit:

    ```css
    :root {
      --space: 8px;          /* a variable storing a length */
      --space-lg: calc(var(--space) * 3);  /* 24px */
    }
    .card { padding: var(--space-lg); margin-bottom: var(--space); }
    ```

    Variables store *values* (which may contain units like `px` or `rem`); they cannot create genuinely new units. To build a scale, define variables and combine them with `calc()`.

    **[⬆ Back to Top](#table-of-contents)**

51. ### What is the alpha channel in RGBA/HSLA colors?

    The **alpha channel** sets a color's opacity from `0` (fully transparent) to `1` (fully opaque). It applies **only to that color value**, not the whole element:

    ```css
    .overlay { background-color: rgba(0, 0, 0, 0.5); }   /* 50% black */
    .tint    { background-color: hsla(210, 100%, 50%, 0.25); }
    /* Modern syntax also supports alpha in rgb()/hsl(): */
    .modern  { color: rgb(255 0 0 / 0.7); }
    ```

    Because alpha is part of the color, text and borders on the same element stay fully opaque — unlike the `opacity` property (see next).

    **[⬆ Back to Top](#table-of-contents)**

52. ### Difference between opacity and alpha channel?

    | | `opacity` property | Alpha channel (e.g. `rgba`) |
    | --- | --- | --- |
    | **Scope** | Entire element **and all descendants** | Only the single color value |
    | **Affects children?** | Yes — children fade too | No |
    | **Creates stacking context** | Yes (if < 1) | No |

    ```css
    .a { opacity: 0.5; }                       /* whole box + text + children at 50% */
    .b { background: rgba(0,0,0,0.5); color: #fff; } /* bg semi-transparent, text fully opaque */
    ```

    Use alpha colors when you want a translucent background but crisp, fully-opaque content; use `opacity` to fade an entire component.

    **[⬆ Back to Top](#table-of-contents)**

53. ### What are gradients?

    Gradients are **CSS-generated images** that transition smoothly between colors — no image files needed. Three main types:

    ```css
    .linear { background: linear-gradient(to right, #4f46e5, #ec4899); }
    .radial { background: radial-gradient(circle, #fff, #000); }
    .conic  { background: conic-gradient(red, yellow, green, red); }
    .repeat { background: repeating-linear-gradient(45deg, #000 0 10px, #fff 10px 20px); }
    ```

    Because they're images, gradients can be used anywhere an image is accepted (`background-image`, `border-image`, `mask`) and can be layered, animated (via custom properties), and combined with transparency.

    **[⬆ Back to Top](#table-of-contents)**

54. ### Difference between background-size: cover and contain?

    | Value | Behavior |
    | --- | --- |
    | `cover` | Scales image to **fill** the box, preserving aspect ratio; **may crop** edges |
    | `contain` | Scales image to **fit entirely** inside the box, preserving aspect ratio; **may leave gaps** |

    ```css
    .hero  { background-size: cover; }    /* no empty space, possible cropping */
    .logo  { background-size: contain; background-repeat: no-repeat; } /* whole image visible */
    ```

    Use `cover` for full-bleed backgrounds/heroes and `contain` when the entire image must remain visible (logos, product shots). The same keywords apply to the `object-fit` property for `<img>`/`<video>`.

    **[⬆ Back to Top](#table-of-contents)**

55. ### How do you set multiple background images?

    Comma-separate the layers in `background-image` (and matching comma-lists for size/position/repeat). **The first listed layer sits on top:**

    ```css
    .stacked {
      background-image: url(clouds.png), url(stars.jpg);
      background-position: top center, center;
      background-size: contain, cover;
      background-repeat: no-repeat, no-repeat;
    }
    ```

    You can mix gradients and images in the same stack — a common pattern is a dark gradient over a photo to improve text contrast:

    ```css
    .hero {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url(photo.jpg) center/cover;
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

56. ### What is a conic gradient?

    A **conic gradient** transitions colors **around a center point** (like sweeping a clock hand), rather than along a line (linear) or outward from a center (radial). It's perfect for pie charts, color wheels, and loading spinners:

    ```css
    .pie {
      background: conic-gradient(
        #4f46e5 0% 40%,
        #ec4899 40% 75%,
        #10b981 75% 100%
      );
      border-radius: 50%;
    }
    ```

    You can set the starting angle and center: `conic-gradient(from 90deg at 50% 50%, ...)`. `repeating-conic-gradient` creates star-burst and checkerboard effects.

    **[⬆ Back to Top](#table-of-contents)**

57. ### How do you create a transparent background?

    Several approaches depending on intent:

    ```css
    .fully-transparent { background-color: transparent; }       /* see-through */
    .semi-rgba         { background-color: rgba(0, 0, 0, 0.2); } /* 20% black tint */
    .semi-modern       { background-color: rgb(0 0 0 / 20%); }   /* modern syntax */
    ```

    Use `transparent` (a keyword equal to `rgba(0,0,0,0)`) to remove a background, and an alpha color when you want a partial tint that lets content behind show through. Avoid the `opacity` property here — it would also fade the element's text and children.

    **[⬆ Back to Top](#table-of-contents)**

58. ### What does currentColor do?

    `currentColor` is a keyword equal to the element's **computed `color` value**. It lets other properties automatically follow the text color, keeping things in sync without repeating the value:

    ```css
    .icon-button {
      color: #4f46e5;             /* sets text color */
      border: 2px solid currentColor;  /* border matches text */
      fill: currentColor;          /* inline SVG icon matches text */
    }
    .icon-button:hover { color: #ec4899; } /* border + icon update automatically */
    ```

    It's especially powerful for icon systems and themable components — change one `color` and everything derived from `currentColor` follows.

    **[⬆ Back to Top](#table-of-contents)**

59. ### How do you implement dark mode with CSS variables?

    Define theme colors as custom properties on `:root`, then override them inside a `prefers-color-scheme` media query (and/or a manual toggle class):

    ```css
    :root {
      --bg: #ffffff;
      --text: #111111;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #111111;
        --text: #f5f5f5;
      }
    }
    /* Optional manual override */
    [data-theme="dark"] { --bg: #111; --text: #f5f5f5; }

    body { background: var(--bg); color: var(--text); }
    ```

    Components only reference the variables, so the entire UI re-themes by swapping a handful of values — no duplicated rulesets.

    **[⬆ Back to Top](#table-of-contents)**

60. ### Explain the background shorthand.

    The `background` shorthand sets multiple background properties in one declaration: `color`, `image`, `position` / `size`, `repeat`, `attachment`, `origin`, and `clip`. Size must follow position after a slash:

    ```css
    .box {
      background: #eee url(pattern.png) no-repeat center / cover fixed;
      /*          color  image          repeat   position/size  attachment */
    }
    ```

    Any omitted sub-property resets to its initial value, so the shorthand is a clean reset point. For multiple layers, comma-separate complete background definitions. Prefer the shorthand for brevity, longhand when you need to override a single sub-property without disturbing the rest.

    **[⬆ Back to Top](#table-of-contents)**


## Typography & Text

61. ### What is the difference between font-family, font-size, and font-weight?

    | Property | Controls | Example |
    | --- | --- | --- |
    | `font-family` | The typeface, with fallbacks | `"Inter", system-ui, sans-serif` |
    | `font-size` | Text size | `16px`, `1rem`, `clamp(1rem, 2vw, 1.5rem)` |
    | `font-weight` | Boldness (100–900, or `normal`/`bold`) | `400` (normal), `700` (bold) |

    ```css
    body {
      font-family: "Inter", system-ui, sans-serif; /* falls back if Inter missing */
      font-size: 1rem;
      font-weight: 400;
    }
    h1 { font-weight: 700; }
    ```

    Always end `font-family` with a generic fallback (`sans-serif`, `serif`, `monospace`) so text renders even if custom fonts fail.

    **[⬆ Back to Top](#table-of-contents)**

62. ### What are web-safe fonts?

    **Web-safe fonts** are typefaces pre-installed on virtually all operating systems, so they render consistently without downloading anything: Arial, Helvetica, Times New Roman, Georgia, Courier New, Verdana, and the generic `system-ui` stack.

    ```css
    .safe { font-family: Georgia, "Times New Roman", serif; }
    /* Modern "native" stack — uses the OS's own UI font */
    .native {
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
    }
    ```

    They're reliable fallbacks behind custom web fonts and avoid layout shift while a downloaded font loads.

    **[⬆ Back to Top](#table-of-contents)**

63. ### What is @font-face?

    `@font-face` defines a custom font for use on your site, loaded from your own server or a CDN:

    ```css
    @font-face {
      font-family: "MyFont";
      src: url("/fonts/myfont.woff2") format("woff2"),
           url("/fonts/myfont.woff")  format("woff");  /* fallback format */
      font-weight: 400;
      font-display: swap;   /* show fallback text immediately, swap when ready */
    }
    body { font-family: "MyFont", sans-serif; }
    ```

    Prefer `woff2` (smallest, widely supported). Declare separate `@font-face` blocks per weight/style, set matching `font-weight`/`font-style`, and use `font-display` to control loading behavior.

    **[⬆ Back to Top](#table-of-contents)**

64. ### Difference between serif, sans-serif, monospace and cursive fonts?

    | Family | Characteristics | Examples |
    | --- | --- | --- |
    | **Serif** | Small strokes (serifs) at letter ends; traditional, print feel | Times, Georgia |
    | **Sans-serif** | No serifs; clean, modern, common for screens | Arial, Helvetica, Inter |
    | **Monospace** | Every glyph the same width; code/tabular data | Courier, Consolas |
    | **Cursive** | Mimics handwriting/script | Brush Script, Comic Sans |

    ```css
    code { font-family: "Fira Code", Consolas, monospace; }
    h1   { font-family: Georgia, serif; }
    ```

    These five generic families (plus `fantasy`) are the universal fallbacks at the end of any `font-family` list.

    **[⬆ Back to Top](#table-of-contents)**

65. ### What is line-height?

    `line-height` sets the vertical height of each line box — effectively the spacing between lines of text. A **unitless** value is recommended because it multiplies each element's own font size and inherits sensibly:

    ```css
    body { line-height: 1.5; }   /* 1.5 × the element's font-size, scales with children */
    ```

    Unitless `1.4`–`1.6` is the readability sweet spot for body text. Headings often use tighter values (`1.1`–`1.25`).

    **[⬆ Back to Top](#table-of-contents)**

66. ### Difference between line-height: normal, unitless and fixed values?

    | Value | Meaning | Inheritance behavior |
    | --- | --- | --- |
    | `normal` | Browser default (~1.2×) | Computed per element |
    | Unitless (`1.5`) | Multiplier of the element's font size | **Recommended** — children compute from their own size |
    | Length (`24px`) | Fixed height | Inherits the **computed length**, breaking nested scaling |
    | Percentage (`150%`) | Computed once, then inherited as a fixed length | Same trap as length |

    ```css
    .good { line-height: 1.5; }   /* a 32px heading inside gets 48px lines */
    .bad  { line-height: 24px; }  /* the 32px heading still gets cramped 24px lines */
    ```

    Always prefer the **unitless** form to avoid passing an inappropriate fixed line-height into larger nested text.

    **[⬆ Back to Top](#table-of-contents)**

67. ### What is letter spacing?

    `letter-spacing` adjusts the horizontal space **between characters** (tracking). Positive values spread letters apart; negative values tighten them:

    ```css
    .heading { letter-spacing: 0.05em; }   /* slightly airy uppercase heading */
    .tight   { letter-spacing: -0.02em; }  /* tighten large display text */
    .caps     { text-transform: uppercase; letter-spacing: 0.1em; }
    ```

    Using `em` keeps the spacing proportional to the font size. Subtle adjustments improve readability of all-caps and large headings; avoid over-spacing body text.

    **[⬆ Back to Top](#table-of-contents)**

68. ### What is word spacing?

    `word-spacing` controls the gap **between words** (in addition to the normal space character width):

    ```css
    .spaced { word-spacing: 0.25em; }
    .justified { text-align: justify; word-spacing: 0.05em; }
    ```

    It's used less often than `letter-spacing`, mainly to fine-tune justified text or stylistic headings. Like letter-spacing, prefer relative units so it scales with font size.

    **[⬆ Back to Top](#table-of-contents)**

69. ### What does text-align do?

    `text-align` sets the **horizontal alignment of inline content** (text, inline images) within its block:

    | Value | Effect |
    | --- | --- |
    | `left` / `start` | Align to the start edge (LTR: left) |
    | `right` / `end` | Align to the end edge |
    | `center` | Center within the box |
    | `justify` | Stretch lines to both edges (except last) |

    ```css
    .lead { text-align: center; }
    article p { text-align: start; }  /* respects writing direction */
    ```

    Prefer logical `start`/`end` over `left`/`right` for internationalization (RTL languages). It aligns inline content, not block-level boxes — center a block with `margin: auto` or flex/grid instead.

    **[⬆ Back to Top](#table-of-contents)**

70. ### Difference between text-decoration and text-transform?

    | Property | Purpose | Values |
    | --- | --- | --- |
    | `text-decoration` | Adds lines to text | `underline`, `overline`, `line-through`, `none` |
    | `text-transform` | Changes letter case | `uppercase`, `lowercase`, `capitalize`, `none` |

    ```css
    a { text-decoration: none; }              /* remove default underline */
    a:hover { text-decoration: underline wavy red; } /* style/color/thickness */
    .label { text-transform: uppercase; }     /* visually uppercase, source unchanged */
    ```

    `text-transform` only changes *display*, not the underlying text — screen readers and copy/paste use the original casing. The modern `text-decoration` shorthand also accepts line style, color, and thickness.

    **[⬆ Back to Top](#table-of-contents)**

71. ### What does white-space control?

    `white-space` governs how whitespace and line breaks inside an element are handled:

    | Value | Collapses spaces? | Wraps lines? | Preserves `\n`? |
    | --- | --- | --- | --- |
    | `normal` | Yes | Yes | No |
    | `nowrap` | Yes | **No** | No |
    | `pre` | **No** | No | Yes |
    | `pre-wrap` | No | Yes | Yes |
    | `pre-line` | Yes | Yes | Yes |

    ```css
    code.block { white-space: pre; }       /* keep code formatting verbatim */
    .ellipsis  { white-space: nowrap; }    /* force single line (for truncation) */
    .message   { white-space: pre-wrap; }  /* honor user line breaks but still wrap */
    ```

    **[⬆ Back to Top](#table-of-contents)**

72. ### How do you truncate text with ellipsis?

    For a **single line**, combine three properties:

    ```css
    .truncate {
      white-space: nowrap;      /* prevent wrapping */
      overflow: hidden;         /* clip the overflow */
      text-overflow: ellipsis;  /* show … */
      max-width: 200px;
    }
    ```

    For **multiple lines**, use the line-clamp pattern:

    ```css
    .clamp {
      display: -webkit-box;
      -webkit-line-clamp: 3;        /* show 3 lines, then … */
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
    ```

    The element needs a constrained width (single-line) for the ellipsis to appear.

    **[⬆ Back to Top](#table-of-contents)**

73. ### What is vertical-align?

    `vertical-align` aligns **inline-level and table-cell** elements relative to the surrounding line or cell — it does **not** vertically center block elements (use flex/grid for that):

    ```css
    img.icon { vertical-align: middle; }    /* align inline icon with text */
    sup { vertical-align: super; }
    td  { vertical-align: top; }             /* table cell content to the top */
    ```

    Values include `baseline` (default), `top`, `middle`, `bottom`, `sub`, `super`, `text-top`, and length/percentage offsets. A frequent gotcha: it has no effect on block-level elements.

    **[⬆ Back to Top](#table-of-contents)**

74. ### How to improve readability using typography?

    Key levers, with sensible defaults:

    ```css
    .prose {
      font-size: 1.125rem;       /* comfortable body size */
      line-height: 1.6;          /* 1.4–1.6 for body text */
      max-width: 65ch;           /* ~60–75 characters per line */
      letter-spacing: 0.01em;
      color: #222;               /* sufficient contrast (WCAG AA ≥ 4.5:1) */
    }
    .prose h2 { line-height: 1.2; margin-top: 2em; }  /* breathing room */
    ```

    Best practices: moderate measure (line length), generous spacing/margins, strong contrast, a clear type scale, and responsive sizing with `clamp()`. Avoid tiny fonts, long lines, and low-contrast gray-on-gray.

    **[⬆ Back to Top](#table-of-contents)**

75. ### What is font loading behaviour?

    While a custom font downloads, the browser must decide what to show. It can render invisible text (**FOIT** — Flash of Invisible Text) or fallback text that later swaps (**FOUT** — Flash of Unstyled Text). The `font-display` descriptor in `@font-face` controls this trade-off:

    ```css
    @font-face {
      font-family: "MyFont";
      src: url("/fonts/myfont.woff2") format("woff2");
      font-display: swap;   /* avoid invisible text; show fallback then swap */
    }
    ```

    To minimize layout shift, also preload critical fonts (`<link rel="preload" as="font" crossorigin>`) and choose fallback fonts with similar metrics (`size-adjust`, `ascent-override`).

    **[⬆ Back to Top](#table-of-contents)**

76. ### What is font-display?

    `font-display` tells the browser how to handle the gap between requesting a web font and it becoming available:

    | Value | Block period | Swap period | Effect |
    | --- | --- | --- | --- |
    | `auto` | Browser default | — | Usually FOIT |
    | `block` | Short (~3s) invisible | Infinite | Avoids FOUT, risks invisible text |
    | `swap` | None | Infinite | Fallback shown immediately, then swaps (FOUT) |
    | `fallback` | Tiny | Short | Compromise; gives up if slow |
    | `optional` | Tiny | None | Font is optional; best for performance |

    ```css
    @font-face { font-family: "Body"; src: url(body.woff2) format("woff2"); font-display: swap; }
    ```

    `swap` is the common choice for body text; `optional` is best when avoiding layout shift matters more than using the exact font.

    **[⬆ Back to Top](#table-of-contents)**

77. ### What are variable fonts?

    A **variable font** packs many variations (weight, width, slant, optical size) into a **single file**, interpolating continuously between them. This cuts file size versus shipping many static weights and enables smooth animation:

    ```css
    @font-face {
      font-family: "Inter var";
      src: url("/fonts/inter.var.woff2") format("woff2-variations");
      font-weight: 100 900;   /* the supported range */
    }
    h1 {
      font-family: "Inter var";
      font-variation-settings: "wght" 650, "slnt" -4;
      /* or the high-level: font-weight: 650; */
    }
    ```

    You can animate any axis, giving fine-grained control with one network request.

    **[⬆ Back to Top](#table-of-contents)**

78. ### How can you make typography responsive?

    Combine relative units with `clamp()` for fluid type that scales between bounds without media queries:

    ```css
    h1 {
      /* clamp(MIN, PREFERRED, MAX) */
      font-size: clamp(1.75rem, 1rem + 3vw, 3rem);
      line-height: 1.2;
    }
    body { font-size: clamp(1rem, 0.95rem + 0.4vw, 1.125rem); }
    ```

    `clamp()` keeps text readable on small screens (the min), scales smoothly with the viewport (the `vw` term), and caps growth on large screens (the max). Unitless `line-height` and `ch`-based `max-width` complete a robust responsive type system.

    **[⬆ Back to Top](#table-of-contents)**

79. ### How do you center text vertically and horizontally?

    The reliable modern way is flexbox or grid on the container:

    ```css
    /* Flexbox */
    .center {
      display: flex;
      justify-content: center;  /* horizontal */
      align-items: center;      /* vertical */
      min-height: 100vh;
    }
    /* Grid — even terser */
    .center-grid {
      display: grid;
      place-items: center;
      min-height: 100vh;
    }
    ```

    For a single line of text, `text-align: center` plus a matching `line-height` equal to the container height also works, but flex/grid handle multi-line and dynamic content gracefully.

    **[⬆ Back to Top](#table-of-contents)**

80. ### Explain text-overflow: clip vs. ellipsis.

    `text-overflow` styles how clipped inline content is signaled (it requires `overflow: hidden` and usually `white-space: nowrap`):

    | Value | Behavior |
    | --- | --- |
    | `clip` (default) | Cuts the text off sharply, mid-character if needed |
    | `ellipsis` | Truncates and appends `…` to signal more text |

    ```css
    .clip     { white-space: nowrap; overflow: hidden; text-overflow: clip; }
    .ellipsis { white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
    ```

    `ellipsis` is friendlier because it tells the user content was truncated. You can even supply a custom string in some engines: `text-overflow: " →";`.

    **[⬆ Back to Top](#table-of-contents)**

81. ### What is writing-mode?

    `writing-mode` sets whether text flows horizontally or vertically and its block direction — essential for languages like Japanese/Chinese vertical text and for creative layouts (rotated labels):

    | Value | Flow |
    | --- | --- |
    | `horizontal-tb` (default) | Left-to-right, top-to-bottom |
    | `vertical-rl` | Top-to-bottom, columns right-to-left |
    | `vertical-lr` | Top-to-bottom, columns left-to-right |

    ```css
    .vertical-label {
      writing-mode: vertical-rl;
      text-orientation: mixed;
    }
    ```

    It also redefines what "block" and "inline" axes mean, which is why logical properties (`margin-block`, etc.) adapt automatically.

    **[⬆ Back to Top](#table-of-contents)**

82. ### What does unicode-bidi do?

    `unicode-bidi` works with the `direction` property to control the **bidirectional (bidi) algorithm** for mixing left-to-right and right-to-left scripts (e.g., Arabic/Hebrew with embedded English):

    ```css
    .rtl {
      direction: rtl;
      unicode-bidi: bidi-override;  /* force the specified direction */
    }
    ```

    Values include `normal`, `embed`, `isolate`, `bidi-override`, and `isolate-override`. In modern markup, the HTML `dir` attribute and `unicode-bidi: isolate` (often via the `<bdi>` element) handle most cases; this property is a low-level control rarely needed directly.

    **[⬆ Back to Top](#table-of-contents)**

83. ### How do you implement drop caps?

    Use the `::first-letter` pseudo-element to enlarge and float the opening letter:

    ```css
    .article p:first-of-type::first-letter {
      float: left;
      font-size: 3.5rem;
      line-height: 1;
      padding-right: 0.1em;
      font-weight: 700;
    }
    ```

    `::first-letter` automatically targets the first letter (including a leading punctuation mark). The modern `initial-letter` property (`initial-letter: 3;`) is a purpose-built alternative with growing support.

    **[⬆ Back to Top](#table-of-contents)**

84. ### What is text-shadow?

    `text-shadow` adds one or more shadows behind text: `offset-x offset-y blur-radius color`:

    ```css
    .title  { text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
    /* Multiple shadows for a glow/outline effect */
    .glow   { text-shadow: 0 0 4px #fff, 0 0 8px #4f46e5; }
    .outline{ text-shadow: -1px -1px 0 #000, 1px 1px 0 #000; }
    ```

    The blur radius is optional (defaults to 0 for a hard shadow). Comma-separate multiple shadows; the first is rendered on top. Use it sparingly to maintain legibility and contrast.

    **[⬆ Back to Top](#table-of-contents)**

85. ### What is line-clamp and -webkit-line-clamp?

    `-webkit-line-clamp` truncates **multi-line** text to a fixed number of lines and adds an ellipsis. It requires the legacy flexbox box model context:

    ```css
    .clamp {
      display: -webkit-box;
      -webkit-line-clamp: 3;          /* keep 3 lines */
      line-clamp: 3;                  /* standard property, gaining support */
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
    ```

    Despite the vendor prefix, it's broadly supported across browsers. The unprefixed `line-clamp` is being standardized. It's the standard solution for card descriptions and previews that must fit a fixed height.

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is hyphenation?

    The `hyphens` property lets the browser break and hyphenate words at language-appropriate points, improving justified text and narrow columns:

    ```css
    .article {
      hyphens: auto;       /* browser inserts hyphens as needed */
      -webkit-hyphens: auto;
    }
    ```

    | Value | Effect |
    | --- | --- |
    | `none` | Never hyphenate |
    | `manual` | Only at `&shy;` (soft hyphen) or `­` |
    | `auto` | Browser decides (needs a `lang` attribute) |

    `auto` requires the element/document to declare a language (`<html lang="en">`) so the browser knows the hyphenation dictionary.

    **[⬆ Back to Top](#table-of-contents)**

87. ### How do you use CSS counters for numbered lists?

    CSS counters create custom numbering without manual numbers in markup, using `counter-reset`, `counter-increment`, and the `counter()` function:

    ```css
    ol.custom { counter-reset: item; list-style: none; }
    ol.custom li { counter-increment: item; }
    ol.custom li::before {
      content: counter(item) ". ";
      font-weight: bold;
      color: #4f46e5;
    }
    /* Nested numbering like 1.1, 1.2 */
    ol.nested li::before { content: counters(item, ".") " "; }
    ```

    Counters are great for stylized lists, section numbering (`h2::before { content: counter(section) }`), and step indicators — all controlled purely in CSS.

    **[⬆ Back to Top](#table-of-contents)**

88. ### What is the overflow-wrap property?

    `overflow-wrap` (formerly `word-wrap`) decides whether the browser may break a long, otherwise-unbreakable string (like a URL) to prevent overflow:

    ```css
    .content {
      overflow-wrap: break-word;  /* break only if the word would overflow */
    }
    .anywhere { overflow-wrap: anywhere; } /* allows breaks more aggressively */
    ```

    | Value | Effect |
    | --- | --- |
    | `normal` | Break only at normal points (spaces, hyphens) |
    | `break-word` | Break long words as a last resort to avoid overflow |
    | `anywhere` | Like break-word but also affects min-content size |

    It's the gentle, content-preserving fix for long URLs/strings, unlike the more aggressive `word-break: break-all`.

    **[⬆ Back to Top](#table-of-contents)**

89. ### What is word-break?

    `word-break` specifies how breaks happen **within words**:

    | Value | Effect |
    | --- | --- |
    | `normal` | Default breaking rules |
    | `break-all` | Break between **any** two characters (common for CJK or forcing fit) |
    | `keep-all` | Never break CJK text between characters |

    ```css
    .force-fit { word-break: break-all; }  /* break anywhere to fit a narrow box */
    ```

    Difference from `overflow-wrap`: `break-all` breaks words even when they'd fit by other means (can look ragged), whereas `overflow-wrap: break-word` only breaks when necessary. Use `overflow-wrap` for natural text, `word-break: break-all` only when you must hard-fit.

    **[⬆ Back to Top](#table-of-contents)**

90. ### What is tab-size?

    `tab-size` sets how many space-widths a tab character (`\t`) renders as — relevant for `<pre>` blocks and code:

    ```css
    pre, code {
      tab-size: 2;          /* render tabs as 2 spaces */
      -moz-tab-size: 2;
    }
    ```

    The default is `8`, which is usually too wide for code on the web. Setting `tab-size: 2` or `4` matches common editor conventions and keeps displayed code compact and aligned.

    **[⬆ Back to Top](#table-of-contents)**


## Display & Visibility

91. ### What is the display property?

    `display` is the single most important layout property — it determines an element's box type and how it (and its children) are laid out:

    | Value | Behavior |
    | --- | --- |
    | `block` | Full-width box, stacks vertically |
    | `inline` | Flows in text, ignores width/height |
    | `inline-block` | Inline flow but accepts dimensions |
    | `flex` / `inline-flex` | One-dimensional flexbox container |
    | `grid` / `inline-grid` | Two-dimensional grid container |
    | `none` | Removed from layout entirely |
    | `contents` | Box removed, children promoted |
    | `flow-root` | Block that establishes a new BFC |

    ```css
    .card { display: flex; }
    .hidden { display: none; }
    ```

    Modern `display` accepts two-value syntax (`display: inline flex`) describing outer and inner display types.

    **[⬆ Back to Top](#table-of-contents)**

92. ### Difference between block, inline and inline-block?

    | | `block` | `inline` | `inline-block` |
    | --- | --- | --- | --- |
    | **Line behavior** | Starts on a new line, fills width | Flows within text | Flows within text |
    | **width/height** | Respected | **Ignored** | Respected |
    | **Vertical margin/padding** | Pushes layout | Padding shows but doesn't push siblings | Respected |
    | **Examples** | `<div>`, `<p>` | `<span>`, `<a>` | buttons, badges |

    ```css
    span.badge {
      display: inline-block;
      width: 60px; height: 24px;  /* now respected */
      text-align: center;
    }
    ```

    `inline-block` is the bridge — it sits inline with text but behaves like a sized box.

    **[⬆ Back to Top](#table-of-contents)**

93. ### Difference between display: none and visibility: hidden? (revisited)

    To reiterate the key distinction with a practical lens:

    ```css
    .removed { display: none; }       /* gone: no space, no paint, reflows layout */
    .invisible { visibility: hidden; } /* hidden: space kept, no paint, no reflow */
    ```

    - **`display: none`** is best when an element should not exist for now (collapsed accordion panel, conditionally rendered UI). It triggers reflow when toggled.
    - **`visibility: hidden`** is best when you want to hide something **without shifting** surrounding content (e.g., toggling visibility in a grid of equal cells). A hidden parent can still reveal individual children via `visibility: visible`.

    Both remove the element from the accessibility tree.

    **[⬆ Back to Top](#table-of-contents)**

94. ### Difference between visibility: hidden and opacity: 0?

    | | `visibility: hidden` | `opacity: 0` |
    | --- | --- | --- |
    | **Occupies space** | Yes | Yes |
    | **Pointer events** | **Blocked** (not clickable) | **Still active** (clickable!) |
    | **In accessibility tree** | No | Yes (still announced) |
    | **Animatable** | Discrete | Smoothly animatable |

    ```css
    .fade { opacity: 0; transition: opacity 0.3s; }  /* fade in/out smoothly */
    .hide { visibility: hidden; }                    /* truly inert but spaced */
    ```

    A common gotcha: `opacity: 0` elements remain interactive and focusable — add `pointer-events: none` (and manage focus) if you want them inert while invisible.

    **[⬆ Back to Top](#table-of-contents)**

95. ### Does display: none affect accessibility?

    **Yes.** Elements with `display: none` (and `visibility: hidden`) are **removed from the accessibility tree** — screen readers do not announce them. This is correct when content should genuinely be hidden, but problematic if you intend content to be visually hidden yet available to assistive tech.

    For **visually-hidden-but-accessible** content (e.g., skip links, screen-reader labels), use the visually-hidden pattern instead:

    ```css
    .sr-only {
      position: absolute;
      width: 1px; height: 1px;
      padding: 0; margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      white-space: nowrap;
      border: 0;
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

96. ### What is display: contents? (revisited)

    `display: contents` removes the element's own box but keeps its children in the layout flow, as if the wrapper weren't there. The practical payoff is letting a semantic wrapper's children participate directly in a parent flex/grid:

    ```css
    .toolbar { display: flex; gap: 1rem; }
    .toolbar .group { display: contents; } /* its buttons become flex items directly */
    ```

    This avoids "nested flex container" spacing issues. Test with screen readers — earlier browser bugs stripped semantics from elements with `display: contents`, though this is largely resolved in current browsers.

    **[⬆ Back to Top](#table-of-contents)**

97. ### What is display: flow-root? (revisited)

    `display: flow-root` makes an element generate a block box that establishes a **new block formatting context**. Its two headline benefits: it **contains floated children** (no clearfix needed) and **prevents margin collapse** with its children:

    ```css
    .media {
      display: flow-root;  /* wraps around a floated image cleanly */
    }
    .media img { float: left; margin-right: 1rem; }
    ```

    It's the intentional, side-effect-free replacement for the old `overflow: hidden` BFC hack (which could clip shadows/tooltips) and the clearfix pseudo-element trick.

    **[⬆ Back to Top](#table-of-contents)**

98. ### Describe flex and grid display types.

    | | `display: flex` | `display: grid` |
    | --- | --- | --- |
    | **Dimensions** | One axis at a time (row **or** column) | Two axes (rows **and** columns) |
    | **Content vs. layout driven** | Content-first (items size to content) | Layout-first (define tracks) |
    | **Best for** | Toolbars, nav, distributing items in a line | Page layouts, card galleries, 2D alignment |

    ```css
    .nav { display: flex; gap: 1rem; justify-content: space-between; }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    ```

    They compose well — grid for the macro layout, flex for micro alignment inside cells.

    **[⬆ Back to Top](#table-of-contents)**

99. ### What is display: inline-flex?

    `display: inline-flex` creates a **flex container that itself flows inline** with surrounding text/elements (rather than taking a full line like `display: flex`). The children are still laid out by flexbox rules:

    ```css
    .chip {
      display: inline-flex;
      align-items: center;
      gap: 0.25rem;
    }
    ```

    ```html
    <p>Status: <span class="chip">✓ Active</span> right inside the sentence.</p>
    ```

    Use it for small inline components (chips, badges, inline button groups) that need internal flex alignment but should sit within a line of content. `inline-grid` is the grid equivalent.

    **[⬆ Back to Top](#table-of-contents)**

100. ### What is the difference between overflow: auto and overflow: scroll?

     | Value | Scrollbars |
     | --- | --- |
     | `auto` | Appear **only when content overflows** |
     | `scroll` | **Always** shown, even if content fits |

     ```css
     .panel-auto   { overflow: auto; }   /* clean — no scrollbar unless needed */
     .panel-scroll { overflow: scroll; } /* reserves scrollbar gutter always */
     ```

     `auto` is usually preferred for a tidy UI. `scroll` is occasionally used to **prevent layout shift** when content dynamically grows/shrinks across the overflow threshold, since the scrollbar gutter is always reserved (the modern `scrollbar-gutter: stable` is a better tool for that now).

     **[⬆ Back to Top](#table-of-contents)**

101. ### When do you need overflow: hidden?

     Two main reasons:

     1. **Clip overflowing content** — crop images to a container, hide off-screen slide-out panels, enforce fixed-height boxes.
     2. **Establish a block formatting context** — to contain floats or stop margin collapse (though `display: flow-root` is now the cleaner choice).

     ```css
     .avatar {
       width: 64px; height: 64px;
       border-radius: 50%;
       overflow: hidden;   /* clip the square image into a circle */
     }
     .avatar img { width: 100%; height: 100%; object-fit: cover; }
     ```

     Beware: `overflow: hidden` also clips shadows, tooltips, and focus outlines that extend beyond the box.

     **[⬆ Back to Top](#table-of-contents)**

102. ### What is object-fit?

     `object-fit` controls how a **replaced element** (`<img>`, `<video>`) fills its box when the box's aspect ratio differs from the media's:

     | Value | Behavior |
     | --- | --- |
     | `fill` (default) | Stretch to fill, distorting aspect ratio |
     | `cover` | Fill the box, preserve ratio, crop excess |
     | `contain` | Fit entirely inside, preserve ratio, may letterbox |
     | `none` | Intrinsic size, no resizing |
     | `scale-down` | Smaller of `none` or `contain` |

     ```css
     .thumb {
       width: 100%; height: 200px;
       object-fit: cover;   /* fill the thumbnail without distortion */
     }
     ```

     It's the `<img>` equivalent of `background-size` — indispensable for consistent image grids.

     **[⬆ Back to Top](#table-of-contents)**

103. ### What is object-position?

     `object-position` sets **where** the replaced content sits within its box when `object-fit` leaves choice (e.g., which part of a cropped image stays visible):

     ```css
     .hero-img {
       width: 100%; height: 300px;
       object-fit: cover;
       object-position: top center;  /* keep the top of the image (e.g., faces) visible */
     }
     ```

     Accepts keywords (`top`, `center`, `left`) or values (`50% 25%`, `20px 10px`). It's analogous to `background-position`. Defaults to `50% 50%` (centered).

     **[⬆ Back to Top](#table-of-contents)**

104. ### What is visibility: collapse?

     `visibility: collapse` has a special meaning **on table rows, row groups, columns, and column groups**: it removes them as if `display: none`, but **without** affecting the table's overall column/row sizing the way removal would:

     ```css
     tr.hidden-row { visibility: collapse; }  /* hide a table row, keep column widths */
     ```

     Outside table contexts, `collapse` behaves like `visibility: hidden` (element hidden, space preserved). Browser support/behavior for the table case has historically varied, so test if you rely on it.

     **[⬆ Back to Top](#table-of-contents)**

105. ### What is stacking context?

     A **stacking context** is a conceptual 3D layer along the z-axis. Elements inside a context are stacked among themselves and treated as a single unit relative to the outside world — meaning a child's `z-index` can **never** escape its parent's context.

     A new stacking context is created by, among others:
     - The root `<html>` element
     - `position` (relative/absolute) **with** a `z-index` other than `auto`
     - `position: fixed` or `sticky`
     - `opacity` less than 1
     - `transform`, `filter`, `perspective`, `will-change`, `mix-blend-mode`, `isolation: isolate`
     - Flex/grid children with a `z-index`

     ```css
     .parent { position: relative; z-index: 1; }  /* new context */
     .child  { position: absolute; z-index: 9999; } /* still trapped under sibling contexts > 1 */
     ```

     Understanding stacking contexts is the key to debugging "my z-index: 9999 doesn't work" issues.

     **[⬆ Back to Top](#table-of-contents)**

106. ### What is z-index?

     `z-index` controls the **stacking order** (front-to-back) of **positioned** elements and flex/grid children. Higher values render in front:

     ```css
     .modal   { position: fixed; z-index: 1000; }
     .overlay { position: fixed; z-index: 999; }
     .tooltip { position: absolute; z-index: 10; }
     ```

     It only takes effect on elements with `position` other than `static` (or flex/grid items). Crucially, `z-index` values are only compared **within the same stacking context** — a high value in a lower context still sits behind everything in a higher context.

     **[⬆ Back to Top](#table-of-contents)**

107. ### When does z-index not work?

     Common reasons `z-index` appears to do nothing:

     1. **The element isn't positioned** — `z-index` is ignored on `position: static` elements (and non-flex/grid items). Fix: add `position: relative`.
     2. **It's trapped in a stacking context** — a parent with `opacity < 1`, `transform`, `filter`, etc. creates a context the child can't escape. The child competes only with siblings, not the outside world.
     3. **Comparing across contexts** — a `z-index: 9999` inside a context whose parent has `z-index: 1` loses to anything in a sibling context with `z-index: 2`.

     ```css
     /* Broken: parent transform traps the child */
     .card { transform: scale(1); }       /* creates a stacking context */
     .card .badge { position: absolute; z-index: 9999; } /* can't rise above other cards */
     ```

     **[⬆ Back to Top](#table-of-contents)**

108. ### What is order in flexbox?

     The `order` property changes the **visual** order of flex (and grid) items without touching the source/DOM order. Items sort ascending by `order` (default `0`):

     ```css
     .item-a { order: 2; }
     .item-b { order: 1; }  /* renders before item-a visually */
     .item-c { order: -1; } /* renders first */
     ```

     Useful for responsive reordering (e.g., move a sidebar above content on mobile). **Accessibility warning:** `order` only changes paint order, not the DOM — keyboard tab order and screen-reader reading order follow the source, so large reorderings can confuse users.

     **[⬆ Back to Top](#table-of-contents)**

109. ### How does z-index behave with transform?

     Applying any `transform` (even `transform: translateZ(0)` or `scale(1)`) makes an element create a **new stacking context**. Its descendants' `z-index` values are then confined within it — they cannot interleave with elements outside:

     ```css
     .panel { transform: translateY(0); } /* establishes a stacking context */
     .panel .popup { position: absolute; z-index: 9999; }
     /* The popup cannot appear above a sibling .panel with a higher effective stacking order */
     ```

     This is a frequent source of bugs in animated UIs and cards with `transform` hover effects. If a dropdown/tooltip gets clipped behind siblings, a transformed ancestor is often the culprit — consider portaling the element out or removing the transform.

     **[⬆ Back to Top](#table-of-contents)**

110. ### How do you center an element vertically in the viewport?

     The cleanest approaches use flex or grid with a full-viewport min-height:

     ```css
     /* Flexbox */
     body {
       min-height: 100vh;
       display: flex;
       justify-content: center;
       align-items: center;
       margin: 0;
     }
     /* Grid — one line */
     .stage { min-height: 100dvh; display: grid; place-items: center; }
     ```

     Using `100dvh` (dynamic viewport height) instead of `100vh` avoids the mobile browser-chrome jump. For an absolutely positioned element, the transform trick also works (see next question).

     **[⬆ Back to Top](#table-of-contents)**


## Positioning

111. ### What is the difference between position: relative and absolute?

     | | `position: relative` | `position: absolute` |
     | --- | --- | --- |
     | **In normal flow?** | Yes — keeps its space | No — removed from flow |
     | **Offset reference** | Its own original position | Nearest positioned ancestor |
     | **Affects siblings?** | No (offset is visual only) | No (taken out of flow) |

     ```css
     .relative { position: relative; top: 10px; left: 20px; }
     /* shifts visually but still reserves its original slot */

     .anchor { position: relative; }       /* becomes the containing block */
     .anchor .badge {
       position: absolute; top: 0; right: 0; /* pinned to .anchor's corner */
     }
     ```

     A classic pattern: `position: relative` on a parent to serve as the **anchor** for an `absolute` child.

     **[⬆ Back to Top](#table-of-contents)**

112. ### When do you use position: fixed?

     `position: fixed` removes the element from flow and positions it relative to the **viewport**, so it stays put while the page scrolls. Use it for persistent UI:

     ```css
     .sticky-header {
       position: fixed;
       top: 0; left: 0; right: 0;
       z-index: 1000;
     }
     .back-to-top { position: fixed; bottom: 1rem; right: 1rem; }
     ```

     Caveats: a `transform`, `filter`, or `perspective` on an ancestor makes `fixed` position relative to **that ancestor** instead of the viewport — a common surprise. Fixed elements also overlap content, so offset the page (e.g., `padding-top`) to compensate.

     **[⬆ Back to Top](#table-of-contents)**

113. ### How does position: sticky work?

     `position: sticky` is a hybrid: the element behaves like `relative` until it scrolls to a specified threshold, then "sticks" like `fixed` within its scrolling container/parent:

     ```css
     .section-heading {
       position: sticky;
       top: 0;            /* sticks when it reaches the top of the viewport */
       background: #fff;
     }
     ```

     Requirements/gotchas:
     - At least one of `top`/`right`/`bottom`/`left` **must** be set as the threshold.
     - It sticks only **within its parent's box** — once the parent scrolls away, the sticky element goes with it.
     - An ancestor with `overflow: hidden/auto/scroll` can silently break stickiness.

     **[⬆ Back to Top](#table-of-contents)**

114. ### How do you center an absolutely positioned element?

     The transform technique centers regardless of the element's size:

     ```css
     .centered {
       position: absolute;
       top: 50%;
       left: 50%;
       transform: translate(-50%, -50%);  /* shift back by half its own size */
     }
     ```

     The `top/left: 50%` places the element's top-left corner at the container's center; `translate(-50%, -50%)` pulls it back by half its own width/height to truly center it. An alternative when the size is known is `inset: 0; margin: auto;`:

     ```css
     .centered-auto {
       position: absolute;
       inset: 0;
       margin: auto;
       width: 200px; height: 100px;  /* needs explicit size */
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

115. ### Difference between positioning and transform-based movement?

     | | `position` offsets (`top`/`left`) | `transform: translate()` |
     | --- | --- | --- |
     | **Triggers layout (reflow)?** | Yes | **No** (composited) |
     | **Affects other elements?** | Can, via flow changes | No |
     | **Performance for animation** | Janky (reflow/repaint) | Smooth (GPU compositor) |
     | **Stacking context** | Only with z-index | Always creates one |

     ```css
     /* Prefer transform for animating movement */
     .move { transition: transform 0.3s; }
     .move:hover { transform: translateX(10px); }
     ```

     Animate `transform` (and `opacity`) for smooth, 60fps motion; use positional offsets for static placement, not animation.

     **[⬆ Back to Top](#table-of-contents)**

116. ### What is the difference between float and flex?

     | | `float` | `flexbox` |
     | --- | --- | --- |
     | **Original purpose** | Wrap text around images | Flexible 1D layout |
     | **Alignment control** | Minimal | Rich (`justify-content`, `align-items`) |
     | **Equal heights / centering** | Hard (hacks) | Trivial |
     | **Containing floats** | Needs clearfix | N/A |

     ```css
     /* Old float layout (avoid for layout today) */
     .col { float: left; width: 33.33%; }

     /* Modern flex */
     .row { display: flex; gap: 1rem; }
     .col { flex: 1; }
     ```

     Floats remain appropriate for their original job — flowing text around a figure — but flexbox (and grid) replaced them for page/component layout.

     **[⬆ Back to Top](#table-of-contents)**

117. ### What is clear?

     `clear` prevents an element from sitting **beside** preceding floated elements, pushing it below them instead:

     | Value | Effect |
     | --- | --- |
     | `left` | Clear left floats |
     | `right` | Clear right floats |
     | `both` | Clear both sides |
     | `none` | Default — allow floating beside |

     ```css
     .footer { clear: both; }  /* drop below any floated content above */
     /* Clearfix uses clear on a pseudo-element to contain floats */
     .clearfix::after { content: ""; display: block; clear: both; }
     ```

     It only relates to floats. In flex/grid layouts, `clear` is irrelevant.

     **[⬆ Back to Top](#table-of-contents)**

118. ### What is position: static?

     `position: static` is the **default** — the element sits in normal document flow and **ignores** `top`/`right`/`bottom`/`left` and `z-index`:

     ```css
     .normal { position: static; }  /* offset properties have no effect */
     ```

     You rarely write it explicitly, except to **reset** an element back to flow after it was positioned elsewhere (e.g., undoing `position: absolute` at a breakpoint). A static element does not act as a containing block for absolutely positioned descendants.

     **[⬆ Back to Top](#table-of-contents)**

119. ### How do you create equal height columns using CSS?

     Flexbox does it automatically — flex items stretch to the tallest by default (`align-items: stretch`):

     ```css
     .columns {
       display: flex;
       gap: 1rem;
       /* align-items: stretch; is the default — equal heights */
     }
     .columns > * { flex: 1; }
     ```

     Grid does the same within a row:

     ```css
     .grid-cols {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
       gap: 1rem;  /* all cells in a row share the row's height */
     }
     ```

     Before flex/grid, equal heights required hacks (huge padding + negative margin, or table display). Today it's free.

     **[⬆ Back to Top](#table-of-contents)**

120. ### What is a containing block?

     The **containing block** is the rectangle against which an element's sizes and position offsets are resolved. Which ancestor serves as it depends on `position`:

     | Element's position | Containing block |
     | --- | --- |
     | `static` / `relative` | Nearest block-level ancestor's content box |
     | `absolute` | Nearest **positioned** ancestor (non-static) |
     | `fixed` | The viewport (unless a transformed ancestor exists) |

     ```css
     .anchor { position: relative; }  /* establishes a containing block */
     .anchor .pinned { position: absolute; bottom: 0; } /* resolves against .anchor */
     ```

     Percentage widths, `top`/`left` offsets, and `absolute` placement all resolve against the containing block — knowing which ancestor it is explains most positioning behavior.

     **[⬆ Back to Top](#table-of-contents)**


## Flexbox

121. ### What is flexbox?

     **Flexbox** (Flexible Box Layout) is a one-dimensional layout model for distributing space and aligning items along a single axis (a row or a column). It excels at things that were painful with floats: vertical centering, equal spacing, equal heights, and reordering.

     ```css
     .toolbar {
       display: flex;
       align-items: center;       /* vertical centering — trivial */
       justify-content: space-between;
       gap: 1rem;
     }
     ```

     Items can **grow** to fill free space or **shrink** to avoid overflow, making layouts naturally responsive. For two-dimensional layouts (rows *and* columns), reach for Grid.

     **[⬆ Back to Top](#table-of-contents)**

122. ### What are main axis and cross axis?

     Flexbox is defined by two perpendicular axes:

     - **Main axis** — the direction items flow, set by `flex-direction` (default `row` = horizontal). `justify-content` aligns along it.
     - **Cross axis** — perpendicular to the main axis. `align-items`/`align-content` align along it.

     ```css
     .row    { display: flex; flex-direction: row; }    /* main = horizontal, cross = vertical */
     .column { display: flex; flex-direction: column; } /* main = vertical, cross = horizontal */
     ```

     Remembering which property aligns which axis is the key to flexbox: **justify = main, align = cross**.

     **[⬆ Back to Top](#table-of-contents)**

123. ### What is a flex container?

     A **flex container** is any element with `display: flex` or `display: inline-flex`. It establishes a flex formatting context, and its **direct children** automatically become flex items:

     ```css
     .container {
       display: flex;        /* this element is the flex container */
       gap: 1rem;
     }
     ```

     Container-level properties (`flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `align-content`, `gap`) control how items are arranged. Only direct children are affected — grandchildren are not flex items unless their parent is also a flex container.

     **[⬆ Back to Top](#table-of-contents)**

124. ### What are flex items?

     **Flex items** are the direct children of a flex container. They are laid out along the main axis and respond to item-level properties:

     ```css
     .item {
       flex-grow: 1;     /* share extra space */
       flex-shrink: 1;   /* shrink if needed */
       flex-basis: 200px;/* starting size */
       align-self: center; /* override container's align-items for this item */
       order: 2;         /* reorder visually */
     }
     ```

     Text directly inside a flex container is wrapped in an anonymous flex item. Margins on flex items never collapse, and `auto` margins absorb free space (great for pushing one item to the far end).

     **[⬆ Back to Top](#table-of-contents)**

125. ### What is flex-direction?

     `flex-direction` sets the main axis direction (and thus how items flow):

     | Value | Flow |
     | --- | --- |
     | `row` (default) | Left → right |
     | `row-reverse` | Right → left |
     | `column` | Top → bottom |
     | `column-reverse` | Bottom → top |

     ```css
     .nav     { display: flex; flex-direction: row; }
     .sidebar { display: flex; flex-direction: column; gap: 0.5rem; }
     ```

     Changing direction swaps which axis `justify-content` and `align-items` act upon — switching to `column` makes `justify-content` vertical and `align-items` horizontal.

     **[⬆ Back to Top](#table-of-contents)**

126. ### What does justify-content do?

     `justify-content` distributes free space and aligns items along the **main axis**:

     | Value | Effect |
     | --- | --- |
     | `flex-start` (default) | Pack to start |
     | `flex-end` | Pack to end |
     | `center` | Center |
     | `space-between` | Equal space *between* items, none at edges |
     | `space-around` | Equal space around each item |
     | `space-evenly` | Equal space everywhere |

     ```css
     .header { display: flex; justify-content: space-between; }
     /* logo left, nav right with all gaps even */
     ```

     **[⬆ Back to Top](#table-of-contents)**

127. ### What does align-items do?

     `align-items` aligns items along the **cross axis** (it sets the default `align-self` for all items):

     | Value | Effect |
     | --- | --- |
     | `stretch` (default) | Items fill the cross axis |
     | `flex-start` | Align to cross start |
     | `flex-end` | Align to cross end |
     | `center` | Center on the cross axis |
     | `baseline` | Align text baselines |

     ```css
     .row {
       display: flex;
       align-items: center;  /* vertically center items in a row */
     }
     ```

     With the default `stretch`, items of different content heights become equal height automatically.

     **[⬆ Back to Top](#table-of-contents)**

128. ### Difference between align-items and align-content?

     | | `align-items` | `align-content` |
     | --- | --- | --- |
     | **Aligns** | Individual items within their line | Whole **lines** as a group |
     | **Applies when** | Always | Only with **multiple wrapped lines** (`flex-wrap: wrap`) |

     ```css
     .single-line { display: flex; align-items: center; }      /* item alignment */
     .multi-line  {
       display: flex; flex-wrap: wrap;
       align-content: space-between;  /* spaces the rows of wrapped items */
       height: 400px;
     }
     ```

     If items don't wrap (single line), `align-content` has no effect.

     **[⬆ Back to Top](#table-of-contents)**

129. ### What is flex-wrap?

     `flex-wrap` controls whether items stay on one line or wrap onto multiple:

     | Value | Effect |
     | --- | --- |
     | `nowrap` (default) | All items on one line (may overflow/shrink) |
     | `wrap` | Wrap onto new lines as needed |
     | `wrap-reverse` | Wrap, but new lines stack in reverse cross direction |

     ```css
     .tags {
       display: flex;
       flex-wrap: wrap;   /* tags flow onto multiple rows on narrow screens */
       gap: 0.5rem;
     }
     ```

     Without `wrap`, a row of items will compress (per `flex-shrink`) or overflow. Wrapping is essential for responsive item grids built with flex.

     **[⬆ Back to Top](#table-of-contents)**

130. ### What does the gap property do in flexbox?

     `gap` sets consistent spacing **between** flex items without adding edge margins — cleaner than the old `margin` + negative-margin hacks:

     ```css
     .list {
       display: flex;
       gap: 1rem;            /* same gap between every item */
       /* row-gap and column-gap can be set separately */
       gap: 1rem 2rem;       /* row-gap 1rem, column-gap 2rem (when wrapping) */
     }
     ```

     Unlike margins, `gap` only applies between items (no leading/trailing space), and it doesn't collapse. It's now well-supported in flexbox (originally a grid feature). Pair with `flex-wrap: wrap` for tidy multi-row spacing.

     **[⬆ Back to Top](#table-of-contents)**

131. ### Explain flex-grow, flex-shrink, and flex-basis.

     These three item properties (combined in the `flex` shorthand) govern sizing:

     | Property | Controls | Default |
     | --- | --- | --- |
     | `flex-grow` | How much to **grow** into free space (proportional) | `0` |
     | `flex-shrink` | How much to **shrink** when space is tight | `1` |
     | `flex-basis` | The **initial** main-axis size before grow/shrink | `auto` |

     ```css
     .item { flex: 1 1 200px; }
     /*       grow shrink basis — start at 200px, then grow/shrink equally */

     .fixed { flex: 0 0 250px; }   /* never grow or shrink — fixed 250px */
     .a { flex-grow: 2; } .b { flex-grow: 1; } /* a gets twice b's share of extra space */
     ```

     **[⬆ Back to Top](#table-of-contents)**

132. ### What does flex: 1 mean?

     `flex: 1` is shorthand for `flex-grow: 1; flex-shrink: 1; flex-basis: 0%`. It makes items **grow to share free space equally**, ignoring their content size as the starting point:

     ```css
     .row { display: flex; }
     .row > * { flex: 1; }   /* every child takes an equal share of the row */
     ```

     Because `flex-basis` is `0%`, all items start from zero and distribute the **entire** width by their grow factor — yielding truly equal widths (unlike `flex-basis: auto`, which factors in content size first).

     **[⬆ Back to Top](#table-of-contents)**

133. ### What is the default value of flex-shrink?

     The default is `flex-shrink: 1`, meaning flex items **will shrink** proportionally when the container is too small to fit them at their basis sizes:

     ```css
     .item { flex-shrink: 1; }  /* default — shrinks to avoid overflow */
     .keep { flex-shrink: 0; }  /* opt out — keeps its size, may cause overflow */
     ```

     This default is why a row of items compresses on narrow screens rather than overflowing. A frequent bug: a flex item with a large min-content (e.g., a long word or `min-width: auto`) refuses to shrink — fix with `min-width: 0`.

     **[⬆ Back to Top](#table-of-contents)**

134. ### How do you center an element using flexbox?

     Two properties center on both axes:

     ```css
     .center {
       display: flex;
       justify-content: center;  /* main axis (horizontal in a row) */
       align-items: center;      /* cross axis (vertical in a row) */
       min-height: 100vh;        /* give it height to center within */
     }
     ```

     This is the canonical "center anything" solution — it works for unknown sizes, multiple children, and dynamic content. For a single child you can alternatively use `margin: auto` on the child inside a flex container.

     **[⬆ Back to Top](#table-of-contents)**

135. ### How do you create equal-width columns with flexbox?

     Give each item `flex: 1` so they share the row equally:

     ```css
     .columns { display: flex; gap: 1rem; }
     .columns > * { flex: 1; }   /* equal widths regardless of content */
     ```

     If content size shouldn't influence widths at all, `flex: 1 1 0` guarantees perfectly equal columns. To let some columns be wider, vary the grow factor: `flex: 2` takes twice the space of `flex: 1`.

     **[⬆ Back to Top](#table-of-contents)**

136. ### How do you reorder flex items?

     Use the `order` property (default `0`); items render in ascending order value:

     ```css
     .item-1 { order: 3; }
     .item-2 { order: 1; }
     .item-3 { order: 2; }
     /* Visual order: item-2, item-3, item-1 */
     ```

     Commonly used at breakpoints to rearrange layout (e.g., promote a CTA above content on mobile). **Accessibility caveat:** `order` does not change DOM/tab order, so don't rely on it for meaningful reordering that keyboard/screen-reader users must follow.

     **[⬆ Back to Top](#table-of-contents)**

137. ### What is the flex-flow shorthand?

     `flex-flow` combines `flex-direction` and `flex-wrap` into one declaration:

     ```css
     .container {
       display: flex;
       flex-flow: row wrap;     /* = flex-direction: row; flex-wrap: wrap; */
     }
     .vertical { flex-flow: column nowrap; }
     ```

     It's a small convenience but keeps related axis/wrapping settings together. Order is direction then wrap.

     **[⬆ Back to Top](#table-of-contents)**

138. ### Why might flex: 1 0 0 be used instead of flex: 1?

     `flex: 1` expands to `flex: 1 1 0%` — note the **percentage** basis. In some nested or column scenarios a `0%` basis can resolve oddly. Writing `flex: 1 0 0` (a unitless `0` basis, and `flex-shrink: 0`) forces items to start from a true zero size and grow equally, avoiding unexpected shrinking:

     ```css
     .equal { flex: 1 0 0; }   /* grow equally, never shrink, zero basis */
     ```

     In practice `flex: 1` works for most cases; `flex: 1 0 0` is a defensive variant when content or nested flex contexts cause uneven sizing. (Many developers also use `min-width: 0` to fix the related "won't shrink" issue.)

     **[⬆ Back to Top](#table-of-contents)**

139. ### How do you prevent a flex item from shrinking?

     Set `flex-shrink: 0` so the item keeps its basis/size even when space is tight:

     ```css
     .icon {
       flex-shrink: 0;   /* fixed-size icon won't squash */
       width: 40px; height: 40px;
     }
     .label { flex: 1; }  /* the text takes the remaining space and shrinks instead */
     ```

     This is the standard fix for icons, avatars, or buttons that must stay a fixed size next to flexible text. Shorthand: `flex: 0 0 auto` (or `flex: none`).

     **[⬆ Back to Top](#table-of-contents)**

140. ### What is align-self?

     `align-self` overrides the container's `align-items` for a **single** flex item, aligning just that item on the cross axis:

     ```css
     .row { display: flex; align-items: flex-start; }
     .row .featured { align-self: stretch; }  /* this one item fills the height */
     .row .badge    { align-self: center; }   /* this one centers */
     ```

     It accepts the same values as `align-items` (`stretch`, `flex-start`, `flex-end`, `center`, `baseline`) plus `auto` (inherit from the container). Handy when most items share an alignment but one is special.

     **[⬆ Back to Top](#table-of-contents)**

141. ### What is flex-basis: auto?

     `flex-basis: auto` (the default) sizes the item based on its **content and any `width`/`height`** before free space is distributed. This contrasts with `flex-basis: 0`, which ignores content size:

     ```css
     .auto { flex: 1 1 auto; }  /* starts at content/width size, then grows/shrinks */
     .zero { flex: 1 1 0; }     /* ignores content size — equal distribution */
     ```

     With `auto`, an item with more content starts larger, so columns end up unequal. Use `auto` when intrinsic content size should matter; use `0` for perfectly equal columns.

     **[⬆ Back to Top](#table-of-contents)**

142. ### How do you make a vertical flexbox?

     Set `flex-direction: column`, which makes the main axis vertical:

     ```css
     .stack {
       display: flex;
       flex-direction: column;
       gap: 1rem;
     }
     ```

     Now `justify-content` controls vertical distribution and `align-items` controls horizontal alignment. A common full-height pattern pins a footer to the bottom:

     ```css
     .page { display: flex; flex-direction: column; min-height: 100vh; }
     .page main { flex: 1; }   /* main grows, footer sticks to the bottom */
     ```

     **[⬆ Back to Top](#table-of-contents)**

143. ### What is flex-wrap: wrap-reverse?

     `wrap-reverse` wraps items onto multiple lines like `wrap`, but stacks the new lines in the **opposite cross-axis direction** (e.g., new rows appear *above* rather than below):

     ```css
     .reverse-wrap {
       display: flex;
       flex-wrap: wrap-reverse;
     }
     ```

     It effectively flips the cross-axis start and end. Useful for niche layouts where overflow should grow upward, but used rarely compared to plain `wrap`.

     **[⬆ Back to Top](#table-of-contents)**

144. ### What is flex-end?

     `flex-end` is a value for `justify-content`, `align-items`, and `align-self` that aligns content to the **end** of the relevant axis:

     ```css
     .row {
       display: flex;
       justify-content: flex-end;  /* push items to the main-axis end (right in LTR) */
       align-items: flex-end;      /* and to the cross-axis end (bottom in a row) */
     }
     ```

     The logical equivalent `end` respects writing direction. Its counterpart is `flex-start`. (The newer alignment spec also accepts plain `start`/`end`.)

     **[⬆ Back to Top](#table-of-contents)**

145. ### Explain space-between, space-around and space-evenly.

     Three `justify-content` (and `align-content`) distribution values differ in how edge spacing is handled:

     | Value | Edge space | Between space |
     | --- | --- | --- |
     | `space-between` | None | Equal between items |
     | `space-around` | Half-size at edges | Full between items |
     | `space-evenly` | Equal everywhere | Equal between items |

     ```
     space-between:  |A    B    C|
     space-around:   | A   B   C |
     space-evenly:   |  A  B  C  |
     ```

     ```css
     .nav { display: flex; justify-content: space-between; }
     ```

     `space-between` is most common for nav bars; `space-evenly` gives the most visually uniform gaps.

     **[⬆ Back to Top](#table-of-contents)**

146. ### How do you create responsive navigation with flexbox?

     Combine `flex-wrap` with spacing so items reflow on small screens:

     ```css
     .nav {
       display: flex;
       flex-wrap: wrap;
       justify-content: space-between;
       align-items: center;
       gap: 1rem;
     }
     .nav .logo { margin-right: auto; }  /* push links to the right */

     @media (max-width: 600px) {
       .nav { flex-direction: column; align-items: stretch; }
     }
     ```

     On wide screens links sit in a row; when space runs out they wrap, and a media query can stack them into a column. `margin-right: auto` is a neat trick to separate the logo from the link cluster.

     **[⬆ Back to Top](#table-of-contents)**

147. ### What are common flexbox layout issues?

     | Issue | Cause | Fix |
     | --- | --- | --- |
     | Items overflow instead of wrapping | Missing `flex-wrap: wrap` | Add `flex-wrap: wrap` |
     | A flex item won't shrink | Default `min-width: auto` (min-content) | Set `min-width: 0` |
     | Text overflows in a flex child | Same min-content issue | `min-width: 0` + `overflow` |
     | Unequal "equal" columns | `flex-basis: auto` uses content size | Use `flex: 1 1 0` |
     | Stretched images distorted | Default `align-items: stretch` | `align-self: flex-start` or fix dimensions |
     | Percentage height ignored | Parent has no height | Give the flex container a height |

     ```css
     .truncating-child { min-width: 0; overflow: hidden; text-overflow: ellipsis; }
     ```

     The `min-width: 0` fix resolves a huge share of real-world flex bugs.

     **[⬆ Back to Top](#table-of-contents)**

148. ### When should you use flexbox vs. CSS Grid?

     | Use **Flexbox** when… | Use **Grid** when… |
     | --- | --- |
     | Laying out in **one** dimension (row or column) | Laying out in **two** dimensions (rows and columns) |
     | Content size should drive sizing | You want explicit track control |
     | Distributing/aligning items in a line | Aligning items into a defined matrix |
     | Toolbars, nav, button groups, chips | Page layouts, dashboards, card galleries |

     ```css
     .toolbar { display: flex; gap: 1rem; }       /* 1D */
     .dashboard {
       display: grid;
       grid-template-columns: 250px 1fr;
       grid-template-rows: auto 1fr auto;          /* 2D */
     }
     ```

     They're complementary — use grid for the page skeleton and flex for aligning content inside cells.

     **[⬆ Back to Top](#table-of-contents)**

149. ### Can flex and grid be used together?

     **Absolutely** — they nest freely and are designed to complement each other:

     ```css
     .layout {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
       gap: 1rem;
     }
     .card {
       display: flex;          /* flex inside a grid cell */
       flex-direction: column;
     }
     .card .actions { margin-top: auto; display: flex; gap: 0.5rem; } /* pin actions to bottom */
     ```

     A common pattern: Grid arranges the cards; each card is a column flexbox so its footer/actions can be pushed to the bottom with `margin-top: auto`. Mix and match per layout need.

     **[⬆ Back to Top](#table-of-contents)**

150. ### What does min-content do in flexbox and grid?

     `min-content` is a sizing keyword equal to the **smallest size an element can take without its content overflowing** — typically the width of its longest unbreakable word:

     ```css
     .grid { display: grid; grid-template-columns: min-content 1fr; }
     /* first column shrinks to its longest word; second column takes the rest */

     .item { flex-basis: min-content; }
     ```

     Related keywords: `max-content` (size to fit all content on one line, no wrapping) and `fit-content` (clamp between min and max). They're powerful for intrinsic sizing — e.g., a label column that's exactly as wide as its longest label.

     **[⬆ Back to Top](#table-of-contents)**


## CSS Grid

151. ### What is CSS Grid?

     **CSS Grid** is a two-dimensional layout system that divides space into intersecting rows and columns, letting you place items into the resulting cells and areas with precise control over both axes simultaneously:

     ```css
     .grid {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
       grid-template-rows: auto;
       gap: 1rem;
     }
     ```

     Unlike flexbox (one axis at a time), Grid handles rows **and** columns together, making it ideal for page layouts, dashboards, and any matrix-like arrangement. You can define tracks explicitly, name areas, and overlap items.

     **[⬆ Back to Top](#table-of-contents)**

152. ### Difference between Grid and Flexbox?

     | | Flexbox | Grid |
     | --- | --- | --- |
     | **Dimensions** | One (row or column) | Two (rows and columns) |
     | **Approach** | Content-out (items size themselves) | Layout-in (define the grid first) |
     | **Overlap** | Not designed for it | Native (place items on same cell) |
     | **Gaps** | Supported | Supported |
     | **Best at** | Aligning items in a line | Structured 2D layouts |

     ```css
     .flex { display: flex; gap: 1rem; }              /* 1D */
     .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; } /* 2D */
     ```

     Choose based on dimensionality; combine them for real apps.

     **[⬆ Back to Top](#table-of-contents)**

153. ### What is a grid container?

     A **grid container** is an element with `display: grid` or `display: inline-grid`. It establishes a grid formatting context; its **direct children** become grid items placed into the tracks you define:

     ```css
     .container {
       display: grid;
       grid-template-columns: 1fr 1fr 1fr;
       gap: 1rem;
     }
     ```

     Container-level properties define the structure: `grid-template-columns/rows`, `grid-template-areas`, `gap`, `justify-items`, `align-items`, `grid-auto-flow`, etc.

     **[⬆ Back to Top](#table-of-contents)**

154. ### What is a grid item?

     A **grid item** is a direct child of a grid container. By default items auto-place into cells in source order, but you can position them explicitly:

     ```css
     .item {
       grid-column: 1 / 3;   /* span columns 1–2 */
       grid-row: 2;          /* in row 2 */
       justify-self: center; /* align within its cell (inline axis) */
       align-self: end;      /* align within its cell (block axis) */
     }
     ```

     Items can span multiple tracks, be placed by line number or named area, and even overlap other items.

     **[⬆ Back to Top](#table-of-contents)**

155. ### Explain grid-template-columns.

     `grid-template-columns` defines the number and size of **columns**. Values can mix fixed sizes, fractions, and functions:

     ```css
     .grid {
       display: grid;
       grid-template-columns: 200px 1fr 1fr;       /* fixed + two flexible */
       grid-template-columns: repeat(4, 1fr);      /* four equal columns */
       grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); /* responsive */
       grid-template-columns: [start] 1fr [mid] 2fr [end]; /* named lines */
     }
     ```

     This single property is where most of a grid's structure is declared. Pair with `repeat()`, `minmax()`, and `auto-fit`/`auto-fill` for powerful responsive layouts with no media queries.

     **[⬆ Back to Top](#table-of-contents)**

156. ### Explain grid-template-rows.

     `grid-template-rows` mirrors columns but defines **row** tracks:

     ```css
     .layout {
       display: grid;
       grid-template-rows: auto 1fr auto;  /* header / flexible body / footer */
       min-height: 100vh;
     }
     ```

     `auto` rows size to their content; `1fr` rows absorb remaining space. This `auto 1fr auto` pattern is the classic sticky-footer page layout. Rows you don't explicitly define are created implicitly (sized by `grid-auto-rows`).

     **[⬆ Back to Top](#table-of-contents)**

157. ### What is the fr unit again?

     `fr` represents a fraction of the **free space** remaining in the grid after fixed tracks and gaps are accounted for:

     ```css
     .grid { grid-template-columns: 100px 1fr 2fr; }
     /* 100px fixed, then remaining space split 1:2 between the other two columns */
     ```

     `fr` is grid's signature unit — it distributes leftover space proportionally and, unlike `%`, correctly subtracts `gap`. `minmax(0, 1fr)` is a common defensive form to let `fr` tracks shrink below their content size.

     **[⬆ Back to Top](#table-of-contents)**

158. ### What are explicit vs. implicit grids?

     - **Explicit grid** — tracks you define with `grid-template-columns`/`-rows`/`-areas`.
     - **Implicit grid** — tracks the browser **auto-creates** when items are placed outside the explicit grid (e.g., more items than defined cells). Their size comes from `grid-auto-rows`/`grid-auto-columns`.

     ```css
     .grid {
       display: grid;
       grid-template-columns: repeat(3, 1fr); /* explicit: 3 columns */
       grid-auto-rows: 150px;                 /* implicit rows are 150px tall */
     }
     /* A 4th, 5th... item creates new implicit rows automatically */
     ```

     **[⬆ Back to Top](#table-of-contents)**

159. ### What is grid-auto-flow?

     `grid-auto-flow` controls how auto-placed items fill the grid:

     | Value | Effect |
     | --- | --- |
     | `row` (default) | Fill row by row |
     | `column` | Fill column by column |
     | `dense` | Backfill earlier gaps with later, smaller items |

     ```css
     .masonry-ish {
       display: grid;
       grid-template-columns: repeat(4, 1fr);
       grid-auto-flow: row dense;  /* fill holes left by spanning items */
     }
     ```

     `dense` packing can reorder items visually (watch accessibility), but it eliminates gaps in galleries where items span different track counts.

     **[⬆ Back to Top](#table-of-contents)**

160. ### What are grid-auto-rows and grid-auto-columns?

     These set the size of **implicitly created** tracks (rows/columns the browser adds beyond the explicit grid):

     ```css
     .grid {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
       grid-auto-rows: minmax(100px, auto);  /* implicit rows: at least 100px, grow with content */
     }
     ```

     Without these, implicit tracks size to their content (`auto`). Setting `grid-auto-rows` gives uniform, predictable row heights as content overflows the explicit definition — common in dynamic card grids.

     **[⬆ Back to Top](#table-of-contents)**

161. ### What is the gap property in Grid?

     `gap` (and its longhands `row-gap`/`column-gap`) sets the gutters between grid tracks — clean, consistent spacing without margins:

     ```css
     .grid {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
       gap: 1rem;          /* equal row and column gaps */
       gap: 2rem 1rem;     /* row-gap 2rem, column-gap 1rem */
     }
     ```

     `gap` only adds space *between* cells (never at the outer edges), and `fr` units correctly account for it. It originated in grid (`grid-gap`) and is now shared with flexbox.

     **[⬆ Back to Top](#table-of-contents)**

162. ### Explain grid-column and grid-row.

     These place/span an item across grid lines. The syntax is `start-line / end-line`:

     ```css
     .item {
       grid-column: 1 / 3;     /* from column line 1 to 3 (spans 2 columns) */
       grid-row: 2 / 4;        /* from row line 2 to 4 (spans 2 rows) */
       grid-column: 1 / -1;    /* span all columns (to the last line) */
       grid-column: span 2;    /* span 2 columns from auto-placed start */
     }
     ```

     Grid lines are numbered starting at 1 (and -1 from the end). `span N` is a relative alternative to absolute line numbers. These two properties (plus `grid-area`) are how you position items precisely.

     **[⬆ Back to Top](#table-of-contents)**

163. ### What is grid-area?

     `grid-area` either names an item (to match a `grid-template-areas` map) or sets all four placement lines at once (`row-start / column-start / row-end / column-end`):

     ```css
     /* As a name */
     .header { grid-area: header; }

     /* As shorthand for the four lines */
     .feature { grid-area: 1 / 1 / 3 / 3; } /* row 1→3, column 1→3 */
     ```

     The named form pairs with `grid-template-areas` for highly readable layouts (see next). The numeric form is a compact way to set `grid-row` and `grid-column` together.

     **[⬆ Back to Top](#table-of-contents)**

164. ### What are named grid areas?

     `grid-template-areas` lets you draw the layout as an ASCII map of named regions, then assign items to those names — extremely readable:

     ```css
     .page {
       display: grid;
       grid-template-columns: 200px 1fr;
       grid-template-rows: auto 1fr auto;
       grid-template-areas:
         "header  header"
         "sidebar content"
         "footer  footer";
       gap: 1rem;
     }
     .header  { grid-area: header; }
     .sidebar { grid-area: sidebar; }
     .content { grid-area: content; }
     .footer  { grid-area: footer; }
     ```

     Use `.` for an empty cell. Reordering the layout is as simple as editing the string map — and it's easy to redefine per breakpoint.

     **[⬆ Back to Top](#table-of-contents)**

165. ### What is the repeat() function?

     `repeat()` expands repetitive track definitions concisely:

     ```css
     .grid { grid-template-columns: repeat(12, 1fr); }      /* 12-column grid */
     .mix  { grid-template-columns: repeat(3, 100px 1fr); } /* pattern repeated 3× */
     .resp { grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); }
     ```

     The first argument is the count (or `auto-fit`/`auto-fill`), the second is the track pattern. Combined with `auto-fit` + `minmax()`, it produces responsive grids that add/remove columns automatically without media queries.

     **[⬆ Back to Top](#table-of-contents)**

166. ### Difference between auto-fill and auto-fit in repeat()?

     Both create as many tracks as fit the container, but differ when items don't fill all tracks:

     | | `auto-fill` | `auto-fit` |
     | --- | --- | --- |
     | Empty tracks | **Kept** (reserved, take space) | **Collapsed** (0 width) |
     | Item stretching | Items stay at min size | Items stretch to fill the row |

     ```css
     .fill { grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); }
     .fit  { grid-template-columns: repeat(auto-fit,  minmax(200px, 1fr)); }
     ```

     With few items: `auto-fit` makes them expand to fill the row; `auto-fill` leaves empty column slots. `auto-fit` is the more common choice for responsive card grids.

     **[⬆ Back to Top](#table-of-contents)**

167. ### What is minmax()?

     `minmax(min, max)` defines a track that's flexible between a floor and ceiling:

     ```css
     .grid {
       grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
       grid-auto-rows: minmax(100px, auto);  /* at least 100px, grow as needed */
     }
     ```

     It's the engine behind responsive grids: each column is at least `250px` but expands to share space (`1fr`) — so the number of columns adapts to the viewport. `minmax(0, 1fr)` is also used to let `fr` tracks shrink below their content size.

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you use minmax() for responsive cards?

     The canonical no-media-query responsive grid:

     ```css
     .cards {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
       gap: 1rem;
     }
     ```

     This reads: "fit as many columns as possible; each is at least 250px wide but grows equally to fill the row." On a wide screen you might get 4 columns; on a phone, 1 — all handled automatically. It's one of the most useful grid patterns in practice.

     **[⬆ Back to Top](#table-of-contents)**

169. ### What is auto in grid tracks?

     An `auto` track sizes to its **content** — growing to fit, or shrinking when space is tight. It's the default for implicit tracks:

     ```css
     .grid {
       grid-template-columns: auto 1fr auto;
       /* first/last columns hug their content; middle takes the rest */
     }
     ```

     `auto` tracks can stretch to absorb leftover space when no `fr` track is present, but `fr` tracks win the free space when both exist. Great for label/content/action rows where the side columns should be content-sized.

     **[⬆ Back to Top](#table-of-contents)**

170. ### What is fit-content()?

     `fit-content(limit)` sizes a track to its content **up to** a maximum, then clamps. It's like `auto` with a ceiling:

     ```css
     .grid {
       grid-template-columns: fit-content(300px) 1fr;
       /* first column grows with content but never exceeds 300px */
     }
     ```

     Effectively `minmax(min-content, limit)` — the track is as small as its content needs but won't blow past the limit, wrapping content instead. Useful for a caption/label column that should be compact but capped.

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do you center items in a grid cell?

     Use the self-alignment properties on an item, or the items-alignment on the container:

     ```css
     /* Single item */
     .item { justify-self: center; align-self: center; }
     .item { place-self: center; }   /* shorthand for both */

     /* All items in the grid */
     .grid { justify-items: center; align-items: center; }
     .grid { place-items: center; } /* shorthand */
     ```

     `justify-*` controls the inline (row) axis, `align-*` controls the block (column) axis. `place-*` combines them. To center the whole grid's tracks within the container, use `justify-content`/`align-content`.

     **[⬆ Back to Top](#table-of-contents)**

172. ### What is the subgrid feature?

     **Subgrid** lets a nested grid adopt its parent's track definitions, so child items align to the **parent's** grid lines instead of creating an independent grid:

     ```css
     .parent {
       display: grid;
       grid-template-columns: repeat(3, 1fr);
     }
     .child {
       grid-column: 1 / -1;
       display: grid;
       grid-template-columns: subgrid;  /* inherit the parent's columns */
     }
     ```

     This solves the long-standing problem of aligning content across nested components (e.g., card headers/footers lining up across a gallery). Support is now broad in modern browsers.

     **[⬆ Back to Top](#table-of-contents)**

173. ### How do you create a masonry layout with CSS Grid?

     True masonry (Pinterest-style staggered columns) is an emerging feature; today there are two practical routes:

     ```css
     /* 1. dense auto-flow — fills gaps but rows still align (pseudo-masonry) */
     .grid {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
       grid-auto-flow: dense;
     }

     /* 2. Native masonry (experimental, behind flags in some browsers) */
     .masonry {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
       grid-template-rows: masonry;   /* not yet broadly supported */
     }
     ```

     Until `grid-template-rows: masonry` ships widely, real masonry usually falls back to CSS columns (`column-count`) or a JS library.

     **[⬆ Back to Top](#table-of-contents)**

174. ### How do you overlay items using grid?

     Place multiple items into the **same cell/area** — by default they stack, controllable with `z-index`:

     ```css
     .stack {
       display: grid;
       grid-template-areas: "stack";
     }
     .stack > * {
       grid-area: stack;   /* every child occupies the same cell */
     }
     .stack .caption { align-self: end; z-index: 1; } /* layer on top */
     ```

     This is a clean way to put a caption over an image or layer UI without `position: absolute`. Items in the same grid area overlap and can be individually aligned and z-ordered.

     **[⬆ Back to Top](#table-of-contents)**

175. ### How can you reorder grid items?

     Several options:

     ```css
     /* 1. Explicit placement by line/area */
     .item-a { grid-column: 3; }
     .item-b { grid-area: header; }

     /* 2. The order property (like flexbox) */
     .item-c { order: -1; }   /* moves earlier in auto-placement */
     ```

     Explicit placement (`grid-column`/`grid-row`/`grid-area`) gives full 2D control and is the grid-idiomatic way. `order` also works on grid items for auto-placed flows. As with flexbox, remember that visual reordering doesn't change DOM/tab order — keep it accessible.

     **[⬆ Back to Top](#table-of-contents)**

176. ### What are implicit named lines?

     When you name lines in a track definition, you can reference those names when placing items — and naming a line `xxx-start`/`xxx-end` auto-creates a named area:

     ```css
     .grid {
       grid-template-columns: [sidebar-start] 200px [sidebar-end content-start] 1fr [content-end];
     }
     .panel { grid-column: sidebar-start / sidebar-end; }
     .main  { grid-column: content-start / content-end; }
     ```

     Conversely, defining `grid-template-areas` implicitly creates `-start`/`-end` named lines for each area. Named lines make placement self-documenting and resilient to track-count changes.

     **[⬆ Back to Top](#table-of-contents)**

177. ### What does grid-template shorthand do?

     `grid-template` combines `grid-template-rows`, `grid-template-columns`, and `grid-template-areas` into one declaration:

     ```css
     .page {
       display: grid;
       grid-template:
         "header  header"  auto
         "sidebar content" 1fr
         "footer  footer"  auto
         / 200px 1fr;     /* column sizes after the slash */
     }
     ```

     Each row string is followed by its row size; column sizes come after the `/`. It's a compact way to declare an entire named layout. (The broader `grid` shorthand also sets auto-flow/implicit tracks.)

     **[⬆ Back to Top](#table-of-contents)**

178. ### What is place-items?

     `place-items` is shorthand for `align-items` and `justify-items`, aligning **all** grid items within their cells on both axes at once:

     ```css
     .grid {
       display: grid;
       place-items: center;        /* center every item in its cell */
       place-items: start center;  /* align-items: start; justify-items: center */
     }
     ```

     A single value applies to both axes; two values are `align` then `justify`. The most famous use is `display: grid; place-items: center;` — the shortest way to perfectly center a single child.

     **[⬆ Back to Top](#table-of-contents)**

179. ### How do you create a CSS grid fallback?

     Use feature queries (`@supports`) to provide an alternative for browsers without grid, or layer grid on top of a sensible default:

     ```css
     /* Fallback: simple float/flex layout */
     .layout > * { float: left; width: 33.33%; }

     @supports (display: grid) {
       .layout { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; }
       .layout > * { float: none; width: auto; }  /* undo fallback */
     }
     ```

     Grid is now supported in all modern browsers, so fallbacks are rarely needed — but `@supports` remains the right tool when you must support legacy environments or progressively enhance.

     **[⬆ Back to Top](#table-of-contents)**

180. ### What is grid-row-gap and grid-column-gap?

     These are the **older, grid-prefixed names** for `row-gap` and `column-gap`. They set spacing between rows and columns respectively:

     ```css
     /* Legacy */
     .grid { grid-row-gap: 1rem; grid-column-gap: 2rem; }
     /* Modern (preferred) */
     .grid { row-gap: 1rem; column-gap: 2rem; }
     /* or the gap shorthand */
     .grid { gap: 1rem 2rem; }  /* row-gap column-gap */
     ```

     The `grid-` prefixed versions are deprecated aliases kept for backwards compatibility. Use the unprefixed `gap`/`row-gap`/`column-gap`, which also work in flexbox.

     **[⬆ Back to Top](#table-of-contents)**


## Responsive Design, Media & Container Queries

181. ### What is responsive web design?

     **Responsive web design (RWD)** is the practice of building sites that adapt to any screen size and device using three core techniques: **fluid grids** (relative units), **flexible media** (`max-width: 100%`), and **media/container queries**. The goal is one codebase that delivers an optimal experience from phones to desktops.

     ```css
     .container { width: 90%; max-width: 1100px; margin-inline: auto; }
     img { max-width: 100%; height: auto; }
     @media (min-width: 768px) { .container { display: grid; grid-template-columns: 1fr 2fr; } }
     ```

     Modern RWD increasingly leans on intrinsic techniques (`clamp()`, `minmax()`, `auto-fit`) that adapt **without** explicit breakpoints.

     **[⬆ Back to Top](#table-of-contents)**

182. ### What are media queries?

     **Media queries** apply CSS conditionally based on device/viewport characteristics — width, height, orientation, resolution, or user preferences:

     ```css
     @media (min-width: 768px) {
       .sidebar { display: block; }
     }
     @media (orientation: landscape) { /* ... */ }
     @media (prefers-color-scheme: dark) { /* ... */ }
     @media print { nav { display: none; } }
     ```

     They're the foundation of adaptive layouts, letting you tailor styles to the environment. Common features: `min-width`/`max-width`, `orientation`, `resolution`, `hover`, `pointer`, and the preference queries.

     **[⬆ Back to Top](#table-of-contents)**

183. ### What is the syntax of a media query?

     `@media [media-type] [and] (feature: value) { rules }`. Media type (`screen`, `print`, `all`) is optional; logical operators combine conditions:

     ```css
     @media screen and (min-width: 600px) and (max-width: 1199px) { /* tablet range */ }
     @media (max-width: 599px), (orientation: portrait) { /* OR */ }
     @media not all and (monochrome) { /* NOT */ }

     /* Level 4 range syntax */
     @media (600px <= width <= 1199px) { /* cleaner range */ }
     ```

     `and` requires all conditions, comma means OR, `not` negates. The newer range syntax (`<=`, `>=`) is more readable than pairing `min-`/`max-`.

     **[⬆ Back to Top](#table-of-contents)**

184. ### Difference between min-width and max-width media queries?

     | | `min-width` | `max-width` |
     | --- | --- | --- |
     | **Applies when** | Viewport is **wider** than value | Viewport is **narrower** than value |
     | **Methodology** | Mobile-first (add as screen grows) | Desktop-first (override as screen shrinks) |

     ```css
     /* Mobile-first: base styles for small, enhance upward */
     .col { width: 100%; }
     @media (min-width: 768px) { .col { width: 50%; } }

     /* Desktop-first: base for large, scale down */
     .col { width: 50%; }
     @media (max-width: 767px) { .col { width: 100%; } }
     ```

     Mobile-first (`min-width`) is generally preferred — it keeps base CSS lean and progressively enhances.

     **[⬆ Back to Top](#table-of-contents)**

185. ### What is mobile-first CSS?

     **Mobile-first** means writing base styles for the **smallest** screen, then layering enhancements for larger screens using `min-width` queries:

     ```css
     /* Base = mobile: single column */
     .grid { display: grid; gap: 1rem; }

     /* Enhance for tablets+ */
     @media (min-width: 768px) {
       .grid { grid-template-columns: 1fr 1fr; }
     }
     @media (min-width: 1100px) {
       .grid { grid-template-columns: repeat(3, 1fr); }
     }
     ```

     Benefits: smaller default CSS (mobile gets only what it needs), better performance on constrained devices, and a natural progressive-enhancement mindset.

     **[⬆ Back to Top](#table-of-contents)**

186. ### What is desktop-first CSS?

     **Desktop-first** starts with the large-screen layout as the base, then uses `max-width` queries to **scale down** for smaller devices:

     ```css
     /* Base = desktop */
     .nav { display: flex; gap: 2rem; }

     @media (max-width: 767px) {
       .nav { flex-direction: column; gap: 0.5rem; }
     }
     ```

     It can suit projects whose primary audience is desktop or that are retrofitting an existing desktop site. The downside: mobile devices download and override more CSS than they need. Mobile-first is usually the better default.

     **[⬆ Back to Top](#table-of-contents)**

187. ### What are breakpoints?

     **Breakpoints** are the viewport widths at which your layout changes via media queries. Rather than chasing specific device sizes, set them where your **content** starts to look cramped or awkward:

     ```css
     /* Common content-driven breakpoints */
     @media (min-width: 480px)  { /* large phones */ }
     @media (min-width: 768px)  { /* tablets */ }
     @media (min-width: 1024px) { /* laptops */ }
     @media (min-width: 1280px) { /* desktops */ }
     ```

     Best practice: choose breakpoints based on where the design breaks, not arbitrary device categories, and keep their number minimal.

     **[⬆ Back to Top](#table-of-contents)**

188. ### How do you decide breakpoints?

     Let the **content** dictate them rather than device specs:

     1. Start mobile and widen the browser slowly.
     2. When the layout looks strained — lines too long, too much whitespace, items too cramped — add a breakpoint there.
     3. Prefer `em`/`rem`-based breakpoints (`@media (min-width: 48em)`) so they respect user zoom.

     ```css
     @media (min-width: 50em) {   /* ~800px, but scales with user font size */
       .prose { columns: 2; }
     }
     ```

     This content-first approach yields fewer, more meaningful breakpoints than memorizing device widths.

     **[⬆ Back to Top](#table-of-contents)**

189. ### What is a fluid layout?

     A **fluid (liquid) layout** uses relative units — percentages, `fr`, `vw`, `auto` — so it scales smoothly with the viewport instead of jumping at fixed breakpoints:

     ```css
     .container { width: 90%; max-width: 1200px; margin-inline: auto; }
     .grid {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
     }
     ```

     Fluid layouts continuously adapt between breakpoints, reducing the number of media queries needed. Combined with `clamp()` for type and `minmax()` for tracks, much responsiveness happens without any explicit breakpoint at all.

     **[⬆ Back to Top](#table-of-contents)**

190. ### What is responsive typography?

     **Responsive typography** adjusts font size, line height, and spacing to the viewport so text stays readable everywhere — ideally fluidly with `clamp()`:

     ```css
     :root { font-size: clamp(100%, 0.9rem + 0.3vw, 112.5%); }
     h1 { font-size: clamp(1.75rem, 1rem + 3vw, 3rem); line-height: 1.15; }
     p  { max-width: 65ch; line-height: 1.6; }
     ```

     `clamp()` scales type between a min and max with the viewport, avoiding both tiny mobile text and oversized desktop text — all without media queries. Constrain measure with `ch` for readability.

     **[⬆ Back to Top](#table-of-contents)**

191. ### What is the clamp() function?

     `clamp(MIN, PREFERRED, MAX)` returns the preferred value, but never below MIN or above MAX — a built-in responsive range in one expression:

     ```css
     h1 { font-size: clamp(1.5rem, 1rem + 2.5vw, 3rem); }
     .container { width: clamp(320px, 90%, 1200px); }
     .gap { gap: clamp(0.5rem, 2vw, 2rem); }
     ```

     The middle value usually mixes a relative unit (`vw`) with a fixed base (`rem`) for smooth, accessible scaling. `clamp()` replaces stacks of media queries for sizing and is one of the most useful modern CSS functions.

     **[⬆ Back to Top](#table-of-contents)**

192. ### How does min() work in CSS?

     `min()` returns the **smallest** of its comma-separated arguments, acting as a responsive cap:

     ```css
     .card { width: min(90%, 600px); }
     /* 90% on small screens, but never wider than 600px */
     .pad  { padding: min(5vw, 3rem); }
     ```

     It's effectively a "max ceiling" expressed inline — the element takes the smaller value, so it never exceeds the fixed bound. Useful for fluid-but-capped widths and spacing without a media query.

     **[⬆ Back to Top](#table-of-contents)**

193. ### How does max() work in CSS?

     `max()` returns the **largest** of its arguments, enforcing a responsive floor:

     ```css
     .sidebar { width: max(250px, 20%); }
     /* at least 250px, but grows to 20% on large screens */
     .tap-target { min-height: max(44px, 3vw); } /* never smaller than 44px */
     ```

     Use it to guarantee a minimum size (e.g., accessible tap targets, readable minimum widths) while still allowing growth. `min()` and `max()` are often combined or nested, and `clamp(a, b, c)` equals `max(a, min(b, c))`.

     **[⬆ Back to Top](#table-of-contents)**

194. ### How do you make images responsive?

     The baseline rule scales images down within their container while preserving aspect ratio:

     ```css
     img {
       max-width: 100%;
       height: auto;     /* preserve aspect ratio */
       display: block;
     }
     ```

     For art direction and performance, use responsive image HTML (`srcset`/`sizes`, `<picture>`) so the browser downloads the right file. `object-fit: cover` helps fit images into fixed-size boxes without distortion, and `aspect-ratio` reserves space to prevent layout shift.

     **[⬆ Back to Top](#table-of-contents)**

195. ### What is object-fit: cover vs. contain again?

     A quick recap in the responsive context:

     ```css
     .thumb { width: 100%; height: 180px; object-fit: cover; }   /* fill, crop edges */
     .logo  { width: 100%; height: 180px; object-fit: contain; } /* fit whole image, letterbox */
     ```

     - **`cover`** — fills the box, preserves ratio, crops overflow. Best for thumbnails/heroes where consistent box size matters more than seeing the whole image.
     - **`contain`** — shows the entire image, preserves ratio, may leave empty space. Best for logos/product shots that must not be cropped.

     Pair with `object-position` to control which part stays visible when cropping.

     **[⬆ Back to Top](#table-of-contents)**

196. ### What is the <picture> element?

     `<picture>` provides **art direction** — serving different image sources for different conditions (viewport, format, resolution). The browser picks the first matching `<source>`, falling back to the required `<img>`:

     ```html
     <picture>
       <source srcset="hero-wide.avif" type="image/avif" media="(min-width: 800px)">
       <source srcset="hero-wide.webp" type="image/webp" media="(min-width: 800px)">
       <source srcset="hero-tall.webp"  media="(max-width: 799px)">
       <img src="hero.jpg" alt="Hero image" width="1200" height="600">
     </picture>
     ```

     Use `<picture>` for different crops/orientations per screen and modern formats with fallbacks; use `<img srcset sizes>` for simple resolution switching of the same image.

     **[⬆ Back to Top](#table-of-contents)**

197. ### What are container queries?

     **Container queries** let a component respond to the size of its **container** rather than the viewport — so the same component adapts correctly anywhere it's placed:

     ```css
     .card-wrapper {
       container-type: inline-size;
       container-name: card;
     }
     @container card (min-width: 400px) {
       .card { display: grid; grid-template-columns: 120px 1fr; }
     }
     ```

     This is a major leap for true component-based responsiveness: a card in a narrow sidebar and the same card in a wide main area can each lay out appropriately, independent of page width.

     **[⬆ Back to Top](#table-of-contents)**

198. ### How are container queries different from media queries?

     | | Media queries | Container queries |
     | --- | --- | --- |
     | **Respond to** | The **viewport** | An ancestor **container's** size |
     | **Scope** | Global/page-level | Component-level |
     | **Reusability** | Component depends on page context | Component adapts wherever placed |

     ```css
     /* Media query: depends on whole screen */
     @media (min-width: 700px) { .card { ... } }

     /* Container query: depends on the card's own container */
     @container (min-width: 400px) { .card { ... } }
     ```

     Container queries make components self-contained and portable, solving the long-standing problem that media queries can't account for where a component sits.

     **[⬆ Back to Top](#table-of-contents)**

199. ### Explain container-type property.

     `container-type` establishes an element as a **query container** so descendants can query its size:

     | Value | Queryable dimensions |
     | --- | --- |
     | `normal` | Not a size container (default) |
     | `inline-size` | Width only (most common, cheapest) |
     | `size` | Both width and height (needs explicit size) |

     ```css
     .panel {
       container-type: inline-size;  /* enable width-based @container queries */
       container-name: panel;        /* optional name */
     }
     /* Shorthand: container: panel / inline-size; */
     ```

     `inline-size` is preferred because querying both dimensions (`size`) requires the container to have a definite height, which can cause layout issues.

     **[⬆ Back to Top](#table-of-contents)**

200. ### How do you write a container query?

     Declare a container, then target it with `@container`:

     ```css
     .product-list { container-type: inline-size; container-name: products; }

     @container products (min-width: 500px) {
       .product { display: grid; grid-template-columns: 1fr 1fr; }
     }
     /* Anonymous container (omit name to match nearest ancestor container) */
     @container (min-width: 500px) { .product { gap: 2rem; } }
     ```

     You can also use container query **units** (`cqw`, `cqi`, `cqh`, `cqb`) that are percentages of the container size — e.g., `font-size: 5cqi` scales with the container's inline size.

     **[⬆ Back to Top](#table-of-contents)**

201. ### What is prefers-color-scheme?

     `prefers-color-scheme` detects whether the user's OS/browser is set to light or dark mode, enabling automatic theming:

     ```css
     :root { --bg: #fff; --fg: #111; }

     @media (prefers-color-scheme: dark) {
       :root { --bg: #111; --fg: #eee; }
     }
     body { background: var(--bg); color: var(--fg); }
     ```

     Combine with CSS variables for clean dark-mode support, and consider a manual toggle (e.g., a `data-theme` attribute) to let users override the system preference. Also pair with `color-scheme: light dark;` so form controls/scrollbars theme correctly.

     **[⬆ Back to Top](#table-of-contents)**

202. ### What is prefers-reduced-motion?

     `prefers-reduced-motion` detects when a user has requested minimal animation (often due to vestibular disorders or motion sensitivity). Respecting it is an accessibility must:

     ```css
     /* Animate by default... */
     .card { transition: transform 0.3s; }

     /* ...but reduce for those who ask */
     @media (prefers-reduced-motion: reduce) {
       *, *::before, *::after {
         animation-duration: 0.01ms !important;
         transition-duration: 0.01ms !important;
         scroll-behavior: auto !important;
       }
     }
     ```

     Always provide reduced or no-motion alternatives; never force large parallax/auto-playing motion on users who opt out.

     **[⬆ Back to Top](#table-of-contents)**

203. ### What is pointer and hover in media queries?

     These **interaction media features** detect input capabilities so you can tailor UI for touch vs. mouse:

     | Feature | Values | Meaning |
     | --- | --- | --- |
     | `hover` | `hover` / `none` | Can the primary input hover? |
     | `pointer` | `fine` / `coarse` / `none` | Pointer precision |

     ```css
     @media (hover: hover) and (pointer: fine) {
       .menu-item:hover { background: #eee; }  /* mouse users get hover effects */
     }
     @media (pointer: coarse) {
       .button { min-height: 48px; }  /* bigger tap targets for touch */
     }
     ```

     This avoids "sticky hover" bugs on touchscreens and ensures touch-friendly target sizes.

     **[⬆ Back to Top](#table-of-contents)**

204. ### What is aspect-ratio in CSS?

     `aspect-ratio` sets a preferred width-to-height ratio, so an element sizes proportionally — invaluable for media boxes and preventing layout shift:

     ```css
     .video {
       aspect-ratio: 16 / 9;
       width: 100%;        /* height derived automatically */
     }
     .avatar { aspect-ratio: 1; width: 64px; }  /* perfect square */
     ```

     It replaces the old padding-top percentage hack. Reserving the ratio before media loads prevents content from jumping (improving Cumulative Layout Shift). If both width and height are set, `aspect-ratio` is ignored.

     **[⬆ Back to Top](#table-of-contents)**

205. ### How do you build accessible responsive tables?

     Keep semantic table markup and handle overflow gracefully:

     ```css
     .table-wrap { overflow-x: auto; }  /* horizontal scroll on small screens */
     table { width: 100%; border-collapse: collapse; }
     th { text-align: start; }

     /* Optional: stack rows into cards on very small screens */
     @media (max-width: 600px) {
       table, thead, tbody, th, td, tr { display: block; }
       thead { position: absolute; left: -9999px; }  /* hide visual header */
       td::before { content: attr(data-label); font-weight: bold; }
     }
     ```

     Use real `<table>`, `<th scope>`, and `<caption>` for screen readers; wrap in an `overflow-x: auto` container so wide tables scroll rather than break the layout. The stacked-card pattern needs `data-label` attributes to keep meaning.

     **[⬆ Back to Top](#table-of-contents)**

206. ### What is @supports rule?

     `@supports` (feature queries) applies CSS only if the browser supports a given property/value — enabling progressive enhancement:

     ```css
     @supports (display: grid) {
       .layout { display: grid; }
     }
     @supports not (backdrop-filter: blur(10px)) {
       .modal { background: rgba(0,0,0,0.9); }  /* fallback for no blur */
     }
     @supports (gap: 1rem) and (display: flex) { /* combined */ }
     ```

     It lets you safely adopt newer features while shipping fallbacks for older browsers, testing actual capability rather than sniffing browsers.

     **[⬆ Back to Top](#table-of-contents)**

207. ### What is calc()?

     `calc()` performs arithmetic mixing different units — essential for layouts that combine fixed and flexible values:

     ```css
     .main { width: calc(100% - 250px); }        /* full width minus a fixed sidebar */
     .box  { height: calc(100vh - 4rem); }        /* viewport minus header */
     .pad  { padding: calc(1rem + 2vw); }
     :root { --space: calc(8px * 2); }
     ```

     Supports `+`, `-`, `*`, `/` (spaces required around `+` and `-`). It works with CSS variables, enabling powerful dynamic sizing, and can be nested. Combine with `min()`/`max()`/`clamp()` for sophisticated responsive math.

     **[⬆ Back to Top](#table-of-contents)**

208. ### How can you prevent horizontal overflow on small screens?

     Common culprits and fixes:

     ```css
     /* 1. Constrain media */
     img, video, iframe { max-width: 100%; height: auto; }

     /* 2. Break long strings */
     .content { overflow-wrap: break-word; }

     /* 3. Fix flex/grid children that won't shrink */
     .flex-child { min-width: 0; }

     /* 4. Avoid fixed widths wider than the viewport */
     .box { width: 100%; max-width: 600px; box-sizing: border-box; }

     /* 5. Last resort diagnostic */
     /* * { outline: 1px solid red; } to find the overflowing element */
     ```

     Most horizontal scroll bugs come from a fixed-width element, an unbreakable string, or a flex item with `min-width: auto`. `box-sizing: border-box` and `min-width: 0` prevent the majority.

     **[⬆ Back to Top](#table-of-contents)**

209. ### What are logical properties?

     **Logical properties** describe layout relative to the **writing direction** (`inline`/`block` axes) instead of physical sides, so layouts adapt automatically to LTR, RTL, and vertical text:

     | Physical | Logical |
     | --- | --- |
     | `margin-left` / `margin-right` | `margin-inline-start` / `margin-inline-end` |
     | `padding-top` / `padding-bottom` | `padding-block-start` / `padding-block-end` |
     | `width` / `height` | `inline-size` / `block-size` |
     | `text-align: left` | `text-align: start` |

     ```css
     .box {
       margin-inline: auto;       /* left+right in LTR, adapts in RTL */
       padding-block: 1rem;       /* top+bottom */
       border-inline-start: 3px solid; /* "leading" edge regardless of direction */
     }
     ```

     They make internationalized UIs far easier — one rule works correctly in every writing mode.

     **[⬆ Back to Top](#table-of-contents)**

210. ### What is the difference between vh and svh / lvh / dvh?

     On mobile, browser UI (address bar) expands and contracts, changing the usable height. The viewport-height units address this:

     | Unit | Refers to |
     | --- | --- |
     | `vh` | Initial/legacy viewport height (often the **large** size) |
     | `svh` | **Small** viewport (UI bars visible) |
     | `lvh` | **Large** viewport (UI bars hidden) |
     | `dvh` | **Dynamic** — updates as UI bars show/hide |

     ```css
     .hero { min-height: 100svh; }  /* always fits, even with the address bar showing */
     .full { height: 100dvh; }      /* tracks the live viewport (may cause reflow) */
     ```

     Use `svh` to guarantee content fits without being cut off by mobile chrome, and `dvh` when you want the element to track the live viewport. They prevent the classic "100vh is too tall on mobile" problem.

     **[⬆ Back to Top](#table-of-contents)**


## Pseudo-classes, Pseudo-elements & Selectors

211. ### What is :hover?

     `:hover` matches an element while the user's pointer is over it — the basis of interactive hover effects:

     ```css
     .btn { background: #4f46e5; transition: background 0.2s; }
     .btn:hover { background: #4338ca; }
     /* Nested: reveal child on parent hover */
     .card:hover .overlay { opacity: 1; }
     ```

     Because touch devices have no real hover, gate hover-only effects behind `@media (hover: hover)` to avoid sticky-hover bugs, and never hide essential functionality behind hover alone (keyboard users can't trigger it).

     **[⬆ Back to Top](#table-of-contents)**

212. ### What is :focus and :focus-visible?

     Both relate to keyboard/programmatic focus, but differ in **when** the indicator shows:

     | | `:focus` | `:focus-visible` |
     | --- | --- | --- |
     | Triggers | Any focus (mouse click too) | Only when a focus ring **should** show (typically keyboard) |

     ```css
     /* Old approach showed rings even on mouse click (often unwanted) */
     button:focus { outline: 2px solid blue; }

     /* Modern: ring only for keyboard users */
     button:focus-visible { outline: 2px solid blue; outline-offset: 2px; }
     button:focus:not(:focus-visible) { outline: none; }
     ```

     `:focus-visible` gives keyboard users clear indicators without showing a ring on every mouse click — the recommended pattern. Never remove focus styles without a visible replacement.

     **[⬆ Back to Top](#table-of-contents)**

213. ### What is :active?

     `:active` matches an element during the moment it's being activated — e.g., the instant between mouse-down and mouse-up on a button:

     ```css
     .btn:active {
       transform: translateY(1px);  /* "pressed" feel */
       background: #3730a3;
     }
     ```

     It provides tactile feedback for clicks/taps. In the cascade, order matters for links: define `:hover` before `:active` (and `:link`/`:visited` before both) — the "LVHA" order (`:link`, `:visited`, `:hover`, `:active`).

     **[⬆ Back to Top](#table-of-contents)**

214. ### What is :visited?

     `:visited` styles links the user has already visited:

     ```css
     a:link    { color: #4f46e5; }
     a:visited { color: #7c3aed; }
     ```

     For **privacy**, browsers heavily restrict what `:visited` can change — only color-related properties (`color`, `background-color`, `border-color`, etc.), and getComputedStyle lies about them — to prevent sites from sniffing your browsing history. You cannot change layout, content, or use it to detect visited state via script.

     **[⬆ Back to Top](#table-of-contents)**

215. ### What is :first-child and :last-child?

     These structural pseudo-classes match an element that is the first or last child of its parent:

     ```css
     li:first-child { border-top: none; }
     li:last-child  { border-bottom: none; }
     /* Remove the trailing margin on the last item */
     .stack > *:last-child { margin-bottom: 0; }
     ```

     Related: `:only-child` (the sole child), `:first-of-type`/`:last-of-type` (first/last of their element type). Note `:first-child` checks position among **all** siblings — if the first child isn't the targeted type, it won't match.

     **[⬆ Back to Top](#table-of-contents)**

216. ### What is :nth-child(n)?

     `:nth-child(n)` selects elements by their position among siblings, accepting numbers, keywords, or `An+B` formulas:

     ```css
     li:nth-child(2)     { /* the 2nd child */ }
     tr:nth-child(odd)   { background: #f5f5f5; } /* zebra striping */
     tr:nth-child(even)  { background: #fff; }
     li:nth-child(3n)    { /* every 3rd: 3,6,9... */ }
     li:nth-child(n+3)   { /* 3rd onward */ }
     li:nth-child(-n+3)  { /* first 3 only */ }
     ```

     The `An+B` syntax is powerful for patterns. Counterparts: `:nth-last-child()` counts from the end, and `:nth-of-type()` counts only same-type siblings.

     **[⬆ Back to Top](#table-of-contents)**

217. ### Difference between :nth-child() and :nth-of-type() again?

     A reinforcing recap: `:nth-child()` counts **all** sibling elements; `:nth-of-type()` counts only siblings of the **same type**:

     ```css
     p:nth-child(2)   { /* matches only if the 2nd child is a <p> */ }
     p:nth-of-type(2) { /* matches the 2nd <p>, ignoring other element types */ }
     ```

     ```html
     <section>
       <h2>Title</h2>   <!-- child 1 -->
       <p>One</p>       <!-- child 2, p-of-type 1 -->
       <p>Two</p>       <!-- child 3, p-of-type 2 -->
     </section>
     <!-- p:nth-child(2) → "One"; p:nth-of-type(2) → "Two" -->
     ```

     Use `:nth-of-type()` when mixed element types make `:nth-child()` unreliable.

     **[⬆ Back to Top](#table-of-contents)**

218. ### What is :not()?

     `:not()` is a negation pseudo-class matching elements that **don't** match the inner selector. In Selectors Level 4 it accepts a complex/list argument:

     ```css
     button:not(.primary) { background: #eee; }
     li:not(:last-child)  { margin-bottom: 0.5rem; }
     :not(h1, h2, h3)     { /* anything that isn't a top heading */ }
     input:not([type="checkbox"]):not([type="radio"]) { width: 100%; }
     ```

     Its specificity equals that of its most specific argument. It's invaluable for "all except" patterns — e.g., spacing all items but the last.

     **[⬆ Back to Top](#table-of-contents)**

219. ### What is :is()?

     `:is()` matches if the element matches **any** selector in its list, dramatically shortening repetitive selectors:

     ```css
     /* Instead of: header h1, header h2, main h1, main h2 { ... } */
     :is(header, main) :is(h1, h2) { margin: 0; }

     :is(.btn, .link):hover { text-decoration: underline; }
     ```

     Its specificity is that of its **most specific** argument (a key difference from `:where()`). It also "forgives" invalid selectors in the list (the rest still work), making it robust.

     **[⬆ Back to Top](#table-of-contents)**

220. ### What is :where()?

     `:where()` works exactly like `:is()` — matches any selector in its list — but has **zero specificity**, making it perfect for low-priority base styles that are easy to override:

     ```css
     :where(h1, h2, h3) { margin: 0; }       /* easily overridden by any later rule */
     :where(.btn) { padding: 0.5rem 1rem; }  /* base styles, no specificity war */
     ```

     ```css
     /* This single class wins because :where() adds 0 specificity */
     .special { margin-top: 2rem; }
     ```

     Use `:where()` for resets and library defaults so consumers can override without `!important`; use `:is()` when you want the selector to carry normal specificity.

     **[⬆ Back to Top](#table-of-contents)**

221. ### What is :has()?

     `:has()` is the long-awaited **relational/"parent" selector** — it matches an element that **contains** something matching the argument:

     ```css
     /* A card that contains an image gets extra padding */
     .card:has(img) { padding-top: 0; }

     /* Style a label when its checkbox is checked */
     label:has(input:checked) { font-weight: bold; }

     /* A form group with an invalid input */
     .field:has(input:invalid) { border-color: red; }

     /* Previous sibling effect: heading followed by a figure */
     h2:has(+ figure) { margin-bottom: 0; }
     ```

     It enables parent and prior-sibling styling that was impossible before, unlocking many JS-free interactions. Supported in all current major browsers.

     **[⬆ Back to Top](#table-of-contents)**

222. ### What are pseudo-elements like ::before and ::after?

     `::before` and `::after` insert **generated content** as the first/last child of an element. They require the `content` property to render:

     ```css
     .quote::before { content: "“"; font-size: 2em; }
     .quote::after  { content: "”"; }

     /* Decorative-only content should be empty to stay out of the a11y tree */
     .icon::before { content: ""; display: inline-block; width: 1em; height: 1em;
                     background: url(icon.svg); }

     /* Pull from an attribute */
     a[href]::after { content: " (" attr(href) ")"; }
     ```

     They're used for icons, decorative shapes, clearfix, tooltips, and counters. They can't be added to replaced elements (`<img>`, `<input>`), and generated content isn't selectable/searchable.

     **[⬆ Back to Top](#table-of-contents)**

223. ### What is ::first-line?

     `::first-line` styles only the **first line** of a block's text — and it's dynamic, re-evaluating as the box width (and thus what fits on line one) changes:

     ```css
     p::first-line {
       font-weight: bold;
       font-variant: small-caps;
       color: #333;
     }
     ```

     Only a limited set of properties apply (font, color, background, word/letter-spacing, text-decoration, etc.) — layout properties like margin don't. Great for editorial intros and lead paragraphs.

     **[⬆ Back to Top](#table-of-contents)**

224. ### What is ::placeholder?

     `::placeholder` styles the placeholder text of form inputs and textareas:

     ```css
     input::placeholder {
       color: #999;
       font-style: italic;
       opacity: 1;   /* Firefox lowers placeholder opacity by default */
     }
     ```

     Keep placeholder contrast sufficient but clearly distinct from entered text, and **never** use placeholders as a replacement for `<label>` — they disappear on input and harm accessibility. Style them subtly to signal they're hints, not values.

     **[⬆ Back to Top](#table-of-contents)**

225. ### What is ::selection?

     `::selection` styles the portion of content the user has highlighted (e.g., dragged over with the cursor):

     ```css
     ::selection {
       background: #4f46e5;
       color: #fff;
     }
     /* Scope to a component */
     .article ::selection { background: #fde68a; color: #000; }
     ```

     Only a small set of properties are allowed: `color`, `background-color`, `text-decoration`, `text-shadow`, and a few others (no layout changes). It's a nice branding touch but keep selected text readable.

     **[⬆ Back to Top](#table-of-contents)**

226. ### How can you chain pseudo-classes?

     Concatenate them (no space) to require **all** conditions simultaneously:

     ```css
     .btn:hover:not(:disabled) { background: #4338ca; }
     input:focus:invalid       { border-color: red; }
     li:first-child:last-child { /* the only child */ }
     a:hover:active            { color: red; }
     ```

     Each appended pseudo-class adds another condition (logical AND). You can also combine pseudo-classes with pseudo-elements: `.link:hover::after { ... }`. Chaining keeps selectors precise without extra classes.

     **[⬆ Back to Top](#table-of-contents)**

227. ### What is specificity of pseudo-classes?

     Most pseudo-classes count as a **class** (specificity 0-0-1-0) — the same as `.class` or `[attr]`:

     ```css
     a:hover { }        /* 0-0-1-1  (one pseudo-class + one type) */
     .menu:first-child { } /* 0-0-2-0 (two classes) */
     ```

     Exceptions:
     - `:where()` always contributes **zero** specificity.
     - `:is()` and `:not()` take the specificity of their **most specific argument**.
     - Pseudo-**elements** (`::before`) count as a type (0-0-0-1), not a class.

     Knowing this prevents accidental specificity escalation, especially with `:is()` vs `:where()`.

     **[⬆ Back to Top](#table-of-contents)**

228. ### What is the difference between single and double colon syntax?

     The single colon (`:`) was the original notation for both pseudo-classes and pseudo-elements in CSS2. CSS3 introduced the double colon (`::`) to **distinguish pseudo-elements** from pseudo-classes:

     ```css
     /* Pseudo-classes — single colon */
     a:hover { }
     /* Pseudo-elements — double colon (preferred) */
     p::before { }
     p::first-line { }
     ```

     For the four legacy pseudo-elements (`::before`, `::after`, `::first-line`, `::first-letter`), browsers accept the single-colon form (`:before`) for backwards compatibility, but you should use `::` for clarity. Newer pseudo-elements (`::selection`, `::placeholder`) require `::`.

     **[⬆ Back to Top](#table-of-contents)**

229. ### Why does :visited have restrictions?

     `:visited` is restricted to protect **user privacy**. Without limits, a page could style visited links differently and then read those styles via script (or infer them through layout/timing) to **detect a user's browsing history** — a real attack discovered years ago:

     ```css
     a:visited { color: purple; }  /* allowed — color only */
     /* a:visited { display: none; } — IGNORED for privacy */
     ```

     Browsers therefore: (1) allow only color-related properties to change, (2) make `getComputedStyle` report the **unvisited** styles, and (3) render visited styles in a way scripts can't observe. This closes the history-sniffing hole.

     **[⬆ Back to Top](#table-of-contents)**

230. ### What is the difference between ::after and :after?

     Functionally **nothing in modern browsers** — both create the same generated-content pseudo-element. The difference is purely notational/historical:

     ```css
     .x::after { content: ""; }  /* CSS3 — preferred, signals "pseudo-element" */
     .x:after  { content: ""; }  /* CSS2 legacy — still works */
     ```

     Use the **double-colon** `::after` for clarity and modern correctness; the single-colon form persists only for backwards compatibility with very old browsers (IE8 and earlier supported only `:after`). There's no behavioral difference today.

     **[⬆ Back to Top](#table-of-contents)**


## Transitions, Animations, Transforms, Performance & Architecture

231. ### What is a CSS transition?

     A **transition** animates a property change smoothly over time instead of jumping instantly. You define which property, how long, the easing, and an optional delay:

     ```css
     .btn {
       background: #4f46e5;
       transition: background 0.3s ease, transform 0.2s ease;
     }
     .btn:hover {
       background: #4338ca;
       transform: translateY(-2px);
     }
     ```

     Transitions fire when a triggering change occurs (`:hover`, class toggle, etc.). They're the simplest way to add polish. Only animatable properties transition (see next), and animating `transform`/`opacity` is the most performant.

     **[⬆ Back to Top](#table-of-contents)**

232. ### Which properties can be transitioned?

     Properties with **interpolatable values** — numbers, lengths, colors, transforms — can be transitioned. Discrete properties (like `display`) historically cannot, though modern CSS adds `transition-behavior: allow-discrete` for some cases.

     | Transitionable | Not (traditionally) |
     | --- | --- |
     | `opacity`, `color`, `background-color` | `display` |
     | `width`, `height`, `margin`, `padding` | `font-family` |
     | `transform`, `box-shadow`, `filter` | `position` keyword |
     | `border-color`, `top`/`left`, `gap` | `visibility` (special — discrete) |

     ```css
     /* Prefer transform & opacity for smooth, GPU-accelerated motion */
     .card { transition: transform 0.3s, opacity 0.3s; }
     ```

     Animating layout properties (`width`, `top`) triggers reflow and can be janky; favor `transform`/`opacity`.

     **[⬆ Back to Top](#table-of-contents)**

233. ### What is transition-property?

     `transition-property` lists which properties to animate. `all` transitions every animatable property (convenient but can cause unintended animations):

     ```css
     .a { transition-property: background-color, transform; }
     .b { transition-property: all; }     /* animate everything that changes */
     .c { transition-property: none; }    /* disable transitions */
     ```

     Naming specific properties is usually better than `all` — it avoids accidentally animating properties you didn't intend and is slightly more performant. Multiple properties are comma-separated and pair positionally with `transition-duration`, etc.

     **[⬆ Back to Top](#table-of-contents)**

234. ### What is transition-duration?

     `transition-duration` sets how long the transition takes, in seconds (`s`) or milliseconds (`ms`):

     ```css
     .fast   { transition-duration: 0.15s; }
     .smooth { transition-duration: 300ms; }
     /* Per-property durations match the property order */
     .multi  {
       transition-property: opacity, transform;
       transition-duration: 0.2s, 0.4s;
     }
     ```

     Typical UI durations are 150–300ms — fast enough to feel responsive, slow enough to perceive. A duration of `0s` means no visible animation. Keep durations short for micro-interactions; reserve longer ones for larger movements.

     **[⬆ Back to Top](#table-of-contents)**

235. ### What is transition-delay?

     `transition-delay` waits a specified time before the transition begins:

     ```css
     .tooltip {
       opacity: 0;
       transition: opacity 0.2s ease 0.5s;  /* wait 0.5s, then fade in over 0.2s */
     }
     .menu:hover .tooltip { opacity: 1; }
     ```

     Negative delays start the transition partway through. Staggered delays create cascade effects (e.g., list items animating in sequence). The shorthand order is `property duration timing-function delay`.

     **[⬆ Back to Top](#table-of-contents)**

236. ### What is transition-timing-function?

     `transition-timing-function` defines the **acceleration curve** — how the property's rate of change varies over the duration:

     | Value | Feel |
     | --- | --- |
     | `linear` | Constant speed |
     | `ease` (default) | Slow start, fast middle, slow end |
     | `ease-in` | Slow start |
     | `ease-out` | Slow end (great for entrances) |
     | `ease-in-out` | Slow both ends |
     | `cubic-bezier(...)` | Custom curve |
     | `steps(n)` | Discrete jumps (sprite animation) |

     ```css
     .enter { transition-timing-function: ease-out; }
     .bounce{ transition-timing-function: cubic-bezier(0.68, -0.55, 0.27, 1.55); }
     ```

     `ease-out` generally feels best for UI elements appearing; `cubic-bezier` gives full custom control.

     **[⬆ Back to Top](#table-of-contents)**

237. ### What is a CSS animation?

     A **CSS animation** runs a sequence of keyframes, offering more control than transitions: it can loop, run without a trigger, have multiple intermediate steps, and play in different directions:

     ```css
     @keyframes pulse {
       0%   { transform: scale(1); opacity: 1; }
       50%  { transform: scale(1.1); opacity: 0.7; }
       100% { transform: scale(1); opacity: 1; }
     }
     .badge {
       animation: pulse 1.5s ease-in-out infinite;
     }
     ```

     Unlike transitions (which need a state change), animations can start automatically and repeat. They're defined with `@keyframes` and applied via the `animation` shorthand and its sub-properties.

     **[⬆ Back to Top](#table-of-contents)**

238. ### What is @keyframes?

     `@keyframes` defines the stages of an animation, either with `from`/`to` or percentage stops:

     ```css
     @keyframes slideIn {
       from { transform: translateX(-100%); opacity: 0; }
       to   { transform: translateX(0);     opacity: 1; }
     }
     @keyframes spin {
       0%   { transform: rotate(0deg); }
       100% { transform: rotate(360deg); }
     }
     .panel { animation: slideIn 0.5s ease-out forwards; }
     .loader { animation: spin 1s linear infinite; }
     ```

     Each stop lists the property values at that point; the browser interpolates between them. `from`/`to` equal `0%`/`100%`. Name the keyframes meaningfully and reference them via `animation-name`.

     **[⬆ Back to Top](#table-of-contents)**

239. ### What is animation-name?

     `animation-name` links an element to one or more `@keyframes` rules by name:

     ```css
     .element {
       animation-name: slideIn;
       animation-duration: 0.5s;
     }
     /* Multiple animations, comma-separated */
     .complex {
       animation-name: slideIn, fadeIn;
       animation-duration: 0.5s, 0.8s;
     }
     ```

     A value of `none` disables the animation. Each named animation pairs positionally with the other `animation-*` sub-properties (duration, timing, etc.). Usually you'll set it via the `animation` shorthand instead.

     **[⬆ Back to Top](#table-of-contents)**

240. ### What is animation-duration?

     `animation-duration` sets the length of **one cycle** of the animation:

     ```css
     .quick  { animation: fadeIn 0.3s; }
     .slow   { animation: float 4s ease-in-out infinite; }
     ```

     Defaults to `0s` (the animation runs instantly = no visible effect, a common "why isn't my animation working?" cause). For looping animations, the duration is per iteration, so total time = duration × iteration-count. Match duration to the motion's scale — subtle micro-animations short, ambient/looping ones longer.

     **[⬆ Back to Top](#table-of-contents)**

241. ### What is animation-fill-mode?

     `animation-fill-mode` controls what styles apply **before** the animation starts and **after** it ends (outside the active period):

     | Value | Effect |
     | --- | --- |
     | `none` (default) | No styles applied outside the run; snaps back |
     | `forwards` | Retains the **last** keyframe after finishing |
     | `backwards` | Applies the **first** keyframe during any delay |
     | `both` | Both forwards and backwards |

     ```css
     .reveal {
       animation: slideIn 0.5s ease-out forwards;  /* stays in final position */
     }
     ```

     `forwards` is the most common — without it, an element snaps back to its pre-animation state when the animation ends.

     **[⬆ Back to Top](#table-of-contents)**

242. ### What is animation-direction?

     `animation-direction` sets whether the animation plays forward, backward, or alternates:

     | Value | Effect |
     | --- | --- |
     | `normal` (default) | Each cycle plays 0% → 100% |
     | `reverse` | Each cycle plays 100% → 0% |
     | `alternate` | Forward, then backward, alternating |
     | `alternate-reverse` | Backward first, then alternating |

     ```css
     .breathe {
       animation: pulse 2s ease-in-out infinite alternate;
       /* smoothly goes out and back instead of jumping at the loop point */
     }
     ```

     `alternate` is great for ping-pong effects (breathing, bouncing) because it avoids the hard jump from 100% back to 0% that `normal` looping causes.

     **[⬆ Back to Top](#table-of-contents)**

243. ### What is animation-iteration-count?

     `animation-iteration-count` sets how many times the animation repeats:

     ```css
     .once     { animation-iteration-count: 1; }       /* default */
     .thrice   { animation-iteration-count: 3; }
     .forever  { animation-iteration-count: infinite; } /* loops endlessly */
     .partial  { animation-iteration-count: 2.5; }      /* fractional allowed */
     ```

     `infinite` is used for spinners, pulsing indicators, and ambient motion. Fractional values stop partway through a cycle. Combine with `alternate` direction for smooth infinite ping-pong loops.

     **[⬆ Back to Top](#table-of-contents)**

244. ### What is animation-play-state?

     `animation-play-state` pauses or resumes a running animation — useful for interactive control (e.g., pause on hover):

     ```css
     .marquee { animation: scroll 10s linear infinite; }
     .marquee:hover { animation-play-state: paused; }   /* pause on hover */
     ```

     ```javascript
     // Toggle from JS
     element.style.animationPlayState = isPlaying ? "running" : "paused";
     ```

     A paused animation freezes at its current frame and resumes from there. It's the clean way to give users control over motion (pairs well with respecting `prefers-reduced-motion`).

     **[⬆ Back to Top](#table-of-contents)**

245. ### What does transform do?

     `transform` applies 2D/3D geometric transformations — moving, scaling, rotating, skewing — **without affecting document flow** (other elements don't shift) and with GPU acceleration:

     ```css
     .move   { transform: translate(20px, 10px); }
     .grow   { transform: scale(1.2); }
     .turn   { transform: rotate(15deg); }
     .combo  { transform: translateX(10px) rotate(5deg) scale(1.1); } /* applied right-to-left */
     .three-d{ transform: perspective(500px) rotateY(30deg); }
     ```

     Because it's composited (no reflow) and doesn't disturb layout, `transform` is the preferred tool for animations. Note: applying any transform creates a new stacking context and containing block for fixed descendants.

     **[⬆ Back to Top](#table-of-contents)**

246. ### Difference between translate, scale, rotate and skew?

     The four core transform functions:

     | Function | Effect | Example |
     | --- | --- | --- |
     | `translate(x, y)` | Moves the element | `translate(10px, 20px)` |
     | `scale(sx, sy)` | Resizes (1 = original) | `scale(1.5)`, `scale(2, 0.5)` |
     | `rotate(angle)` | Rotates around a point | `rotate(45deg)` |
     | `skew(ax, ay)` | Shears/slants | `skew(10deg, 0)` |

     ```css
     .demo {
       transform: translate(10px, 0) scale(1.1) rotate(3deg);
       transform-origin: center;   /* pivot point for scale/rotate */
     }
     ```

     Modern CSS also exposes them as **individual properties** (`translate`, `scale`, `rotate`) that animate independently — handy for composing animations without overwriting the whole `transform`.

     **[⬆ Back to Top](#table-of-contents)**

247. ### Why is transform better than changing top/left for animation?

     Animating `transform` is far smoother than animating `top`/`left` because of the browser rendering pipeline:

     | | `top`/`left` | `transform` |
     | --- | --- | --- |
     | Triggers **layout** (reflow) | Yes (expensive) | No |
     | Triggers **paint** | Often | No (if composited) |
     | Runs on **compositor/GPU** | No | Yes |
     | Result | Janky, drops frames | Smooth 60fps |

     ```css
     /* Janky */   .a { transition: left 0.3s; } .a:hover { left: 20px; }
     /* Smooth */  .b { transition: transform 0.3s; } .b:hover { transform: translateX(20px); }
     ```

     `transform` (and `opacity`) skip layout and paint, letting the GPU composite the change — the foundation of performant animation.

     **[⬆ Back to Top](#table-of-contents)**

248. ### What is will-change?

     `will-change` hints to the browser that a property is about to animate, letting it optimize ahead of time (e.g., promote the element to its own compositor layer):

     ```css
     .modal { will-change: transform, opacity; }
     ```

     **Use sparingly and judiciously:**
     - Don't apply it to many elements — each promoted layer consumes memory.
     - Don't leave it on permanently; add it just before animating (often via JS) and remove it after.
     - Applying it preemptively to everything can *hurt* performance.

     It's a last-resort optimization; most `transform`/`opacity` animations are already smooth without it.

     **[⬆ Back to Top](#table-of-contents)**

249. ### How do you respect reduced motion preferences?

     Honor the user's OS-level motion preference with the `prefers-reduced-motion` media query — an accessibility requirement for users with vestibular sensitivities:

     ```css
     /* Provide motion by default */
     .card { transition: transform 0.3s; }
     @keyframes slideIn { from { transform: translateY(20px); opacity: 0; } to { transform: none; opacity: 1; } }
     .panel { animation: slideIn 0.4s ease-out; }

     /* Pare it back when the user asks */
     @media (prefers-reduced-motion: reduce) {
       *, *::before, *::after {
         animation-duration: 0.01ms !important;
         animation-iteration-count: 1 !important;
         transition-duration: 0.01ms !important;
         scroll-behavior: auto !important;
       }
     }
     ```

     Replace large/parallax motion with subtle fades or none. Treat motion as an enhancement, not a requirement.

     **[⬆ Back to Top](#table-of-contents)**

250. ### What are CSS architecture methodologies?

     As stylesheets grow, naming and organization conventions keep CSS scalable and maintainable. The major approaches:

     | Methodology | Core idea |
     | --- | --- |
     | **BEM** | `Block__Element--Modifier` naming for clear, scoped components |
     | **SMACSS** | Categorize rules: Base, Layout, Module, State, Theme |
     | **OOCSS** | Separate structure from skin; build reusable "objects" |
     | **ITCSS** | Layer styles from generic → specific (inverted triangle) |
     | **Utility-first** | Small single-purpose classes (e.g., Tailwind) |
     | **CSS Modules** | Build-time locally-scoped class names |
     | **CSS-in-JS** | Styles authored in JS, scoped per component, dynamic theming |

     ```css
     /* BEM example */
     .card { }                    /* Block */
     .card__title { }             /* Element */
     .card--featured { }          /* Modifier */
     .card__title--large { }
     ```

     Pick one (or a sensible blend) and apply it consistently. Modern component frameworks often combine scoped styles (CSS Modules/CSS-in-JS) with utility classes. The goal across all of them: predictable specificity, reusability, and avoiding the "append-only" stylesheet sprawl.

     **[⬆ Back to Top](#table-of-contents)**

---

### Disclaimer

The questions and answers in this repository are a curated summary of commonly asked CSS interview questions, spanning fundamentals through advanced modern CSS (flexbox, grid, container queries, logical properties, `:has()`, and more). There is no guarantee that these exact questions will appear in any given interview — the purpose is to help you rapidly review key concepts and build deep understanding. Where the source material was concise, answers have been expanded with additional explanation, comparison tables, and code examples. Contributions and corrections are welcome.

Good luck with your interview 😊

---
