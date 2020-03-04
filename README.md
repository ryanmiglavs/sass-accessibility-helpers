# SASS Accessibility Mixins

Accessibility-oriented SASS mixins to help create a well-designed keyboard UX

The goal is to create a unified, branded, consistent, and pleasant keyboard navigation experience. This can be tricky when handling `:focus` on different types of elements — `input`, `button`, `a`, arbitrary DOM elements.

This helper lib lets you just add a simple mixin to your selector to get you a nice, branded, animated keyboard focus styling.

Just use `@include add-default-focus-styles` on your element and you're set!

If you need to specify your own custom `:focus` styles on an element, you'll instead want to put `@include default-ready-for-focus-styles` to your selected element, then add `@include default-focus-styles` in your element's `:focus` styles.
