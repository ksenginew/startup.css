# startup.css
A starter point to CSS.

Here is my attempt to create starter point to CSS, mostly inspired by modern-normalize and a blog post of Joshua Comeau.

Use this stylesheet before you write CSS for a website.

```css
/* https://github.com/ksenginew/startup.css/blob/main/startup.css */
/**
Use a better box model (opinionated).
*/

*,
::before,
::after {
    box-sizing: border-box;
    margin: 0;
}

/**
More readable line height in all browsers.
Use a more readable tab size.
*/

html {
    line-height: 1.5;
    -moz-tab-size: 4;
    tab-size: 4;
}


/**
Remove the margin in all browsers.
Improve consistency of default fonts in all browsers.
*/

body {
    font-family:
        system-ui,
        -apple-system,
        /* Firefox supports this but not yet `system-ui` */
        'Segoe UI',
        Roboto,
        Helvetica,
        Arial,
        sans-serif,
        'Apple Color Emoji',
        'Segoe UI Emoji';
}

/*
Allow percentage-based heights in the application
*/
html, body {
    height: 100%;
}

/*
Improve media defaults
*/
img, picture, video, canvas, svg {
    display: block;
    max-width: 100%;
}

/*
Remove built-in form typography styles
*/
input, button, textarea, select {
    font: inherit;
}


/**
Improve consistency of default fonts in all browsers.
Correct the odd 'em' font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
    font-family:
        ui-monospace,
        SFMono-Regular,
        Consolas,
        'Liberation Mono',
        Menlo,
        monospace;
    font-size: 1em;
}
```

Licensed under **The Unlicense**. use freely.
