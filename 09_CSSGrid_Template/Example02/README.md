CSS Grid template with CSS variables
```css
//theme colors - http://paletton.com/#uid=44o0s0knkt200++7KJhADkFZU0n
:root {
    --header__bg--color: #d3e33e;
    --nav__bg--color: #e7d33f;
    --main__bg--color: #e7ba3f;
    --footer__bg--color: #b5a4d2;

    --header__text--color: #030300;
    --nav__text--color: #030300;
    --main__text--color: #2f0970;
    --footer__text--color: #b5a4d2;
}

//layout
$header__height: 10;
$main__height: 60;
$footer__height: 9;
$nav__height: calc(#{$header__height} + #{$main__height});

//document.getElementsByTagName("nav")[0].style.gridColumn = "1/1";
$nav__columns: 4;
```
