# JavaScript, TypeScript, and ReactJS

Method and variable names in these languages should be spelled in camelCase, in keeping with
local conventions.

The Prettier code formatter is used on all JS and TS projects without exception.

All code built with Webpack shall be written in TypeScript.  JavaScript is only to be used on
projects where Webpack cannot or will not be used.  Code in JavaScript, TypeScript, JSX, and
TSX must follow the [Airbnb style guide](https://airbnb.io/javascript/react/).

Our preferred JavaScript/TypeScript libraries are React, Redux, and jQuery.

In keeping with library conventions, component names in React should be spelled in PascalCase.

It is preferred to use [our in-house React application template][0] instead of Create-React-App, if
a React app must be used.

[0]: https://github.com/waellison/react-without-cra

Browser features may only be used if they are available to more than 94%[^1] of Web users[^2] as judged
via Can I Use.  This includes CSS, HTML, and DOM.

[^1]: This cutoff exists for HTTP/2, CSS variables, CSS Grid, the WebP image format, and the WebM video
format with VP8, all of which have at least 94% support.  Prefixed CSS features may be used only if an
unprefixed version exists.

[^2]: This must include the supported versions of Microsoft Edge, Google Chrome, Mozilla Firefox, Apple
Safari, Opera, iOS Safari, Android Chrome, Samsung Internet, and Android Firefox released within the
past three years.  We will never support Microsoft Internet Explorer, not even by special request; MSIE
is due to be deprecated in two days as I write this footnote.
