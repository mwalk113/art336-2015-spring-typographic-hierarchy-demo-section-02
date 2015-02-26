# Demo #1: Typographic Hierarchy
With this exercise we are going to explore some of the different typographic HTML tags and redesign their default attributes with Sass and CSS.

@function em($px, $base: $base-font-size) {
    @return ($px / $base) * 1em;
}

body {
    font-size: em(37px);
}