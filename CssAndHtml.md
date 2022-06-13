# CSS and HTML

For parity with identifiers in JavaScript/TypeScript, ID and class selector names in CSS and
HTML should be spelled in camelCase.

Code in CSS must follow the Airbnb style guide aside from the modification listed here.

Unless it is for some reason infeasible, the Less preprocessor should be used for CSS,
allowing for the output of a single, concatenated, minified output file.  Less also provides
for variables, mixins, and other enhancements to standard CSS that reduce the amount of effort
needed by the developer (in a more portable way than CSS variables).

Browser features may only be used if they are available to more than 94% of Web users as
judged via Can I Use.  This includes CSS, HTML, and DOM.  (See also the footnotes on the
JS/React style guide.)
