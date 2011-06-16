#  HTML5 Reset Sass Add-on

This is a Compass / Sass add-on for HTML5 Reset - https://github.com/murtaugh/HTML5-Reset

## HTML5 Reset Summary:

HTML5 Reset (http://html5reset.org) is a simple set of best practices to get web projects off on the right foot.

1. A style sheet designed to strip initial files from browsers, meaning you start off with a blank slate.
2. Easy to customize -- remove whatever you don't need, keep what you do.
3. Analytics and jQuery snippets in place
4. Meta tags ready for population
5. Empty mobile and print style sheets, including blocks for device orientation
6. Modernizr.js [http://www.modernizr.com/](http://www.modernizr.com/) enables HTML5 compatibility with IE (and a dozen other great features)
7. IE-specific classes for simple CSS-targeting
8. iPhone/iPad/iTouch icon snippets
9. Lots of other keen stuff...

## Sass Structure

Sass stylesheets are stored in _/sass and output to _/css/style.css

style.sass is made up of a number of key partials

1. HTML5 Reset - Sass version of HTML5 Reset Templates (https://github.com/murtaugh/HTML5-Reset)
2. Mixins - Don't repeat yourself, use sass mixins (http://sass-lang.com/)
3. Print - Print styles
4. Media - Responsive web design styles
5. Base (optional) - see Compass best practices (http://compass-style.org/help/tutorials/best_practices/)