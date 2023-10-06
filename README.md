# CSS Zen Garden

> From [Wikipedia](https://en.wikipedia.org/wiki/CSS_Zen_Garden)
>
> The **CSS Zen Garden** is a World Wide Web development resource "built to demonstrate what can be accomplished visually through CSS-based design."

----

The source HTML code, `index.html`, not to be modified.

The CSS file, `style.css`, the only file you may modify.

----

View source is a feature, not a bug. Thanks for your curiosity and interest in participating!

Here are the submission guidelines for the new and improved csszengarden.com:

- CSS3? Of course! Prefix for ALL browsers where necessary.
- go responsive; test your layout at multiple screen sizes.
- your browser testing baseline: IE9+, recent Chrome/Firefox/Safari, and iOS/Android
- Graceful degradation is acceptable, and in fact highly encouraged.
- use classes for styling. Don't use ids.
- web fonts are cool, just make sure you have a license to share the files. Hosted services that are applied via the CSS file (ie. Google Fonts) will work fine, but most that require custom HTML won't. TypeKit is supported, see the readme on [this page](https://github.com/mezzoblue/csszengarden.com/) for usage instructions.

And a few tips on building your CSS file:

- use `:first-child`, `:last-child` and `:nth-child` to get at non-classed elements
- use `::before` and `::after` to create pseudo-elements for extra styling
- use multiple background images to apply as many as you need to any element
- use the [Kellum Method](http://goo.gl/GXxdI) for image replacement, if still needed.
- don't rely on the extra divs at the bottom. Use `::before` and `::after` instead.
