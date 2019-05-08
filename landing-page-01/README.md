# Landing Page 01

Simple landing page that snaps into place too.
See for browser compatibility.
"scroll-behaviour" is not available in Firefox, Chrome and Opera. Not available in Safari, Edge and IE. However, you may use JQuery (JS uses more codes) and a lightweight script called "Smooth Scroll".

NB: No JavaScript

# Keynotes

`scroll-behavior: smooth` - Allows the smooth transition or jump from sections of the page.

`scroll-snap-type: y mandatory` - Target the vertical axis scroll feature and imperative. This makes for a more consistent user experience. Beware of a scrolling container taller than the viewport. `mandatory` value will always snape either to the top of the element or the top of the one below, making the middle part of the tall element impossible to scroll to. solution => always make container (targeted page) 100vh size.

`scroll-snap-align: center` - Where the property is placed, it centers on that element.

Not cross-browser compatible (e.g. Opera does not have this feature).

`Element.scrollTop` - The property gets or sets the number of pixels that an element's content is scrolled vertically.

### Discontinued CSS Property

`scroll-snap-points-y` - Defines the vertical positioning of snap points within the content of the scroll container they are applied to. It is similar to `scroll-snap-align`.

## Credits

Youtube _Traversy Media_ [Landing Page With Smooth Scroll - 3 options](https://youtu.be/y9nlfqT4s9s)

[Page Scrolling In Vanilla JavaScript](https://pawelgrzybek.com/page-scroll-in-vanilla-javascript/)