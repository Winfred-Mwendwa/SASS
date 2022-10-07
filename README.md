# SASS
~Store data with sass variables;start with $;e.g. $main-fonts: Arial, sans-serif;

~Sass allows nesting of css rules to organize code by placing child style rules within the respective parent elements

~In Sass, a mixin is a group of CSS declarations that can be reused throughout the style sheet.Mixins are like functions for CSS.The definition starts with @mixin followed by a custom name. The parameters are optional.A mixin is called with the @include directive.

~Newer CSS features take time before they are fully adopted and ready to use in all browsers. As features are added to browsers, CSS rules using them may need vendor prefixes such as -webkit

~use @if @else if and @else to add logic to your styles. They work just like in javascript

~use @for to create a sass loop.
@for is used in two ways: "start through end" or "start to end". The main difference is that the "start to end" excludes the end number as part of the count, and "start through end" includes the end number as part of the count.
#{$i} is the syntax to combine a variable (i) with text to make a string.

~use @each to loop over items in a list or map

~use @while directive to apply a style until  a condition is met

~Partials in Sass are separate files that hold segments of CSS code. These are imported and used in other Sass files. This is a great way to group similar code into a module to keep it organized.

Names for partials start with the underscore (_) character, which tells Sass it is a small segment of CSS and not to convert it into a CSS file. Also, Sass files end with the .scss file extension. To bring the code in the partial into another Sass file, use the @import directive.

~use the @extend directive to reuse the rules written for one element and add more to them in another element
