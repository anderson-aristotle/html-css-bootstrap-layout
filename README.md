[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# CSS: Layout with Bootstrap

## Prerequisites

- [ga-wdi-boston/html-css-layout](https://git.generalassemb.ly/ga-wdi-boston/html-css-layout)
- [ga-wdi-boston/html-css-sass](https://git.generalassemb.ly/ga-wdi-boston/html-css-sass)

## Objectives

By the end of this, developers should be able to:

- Create mobile-first, responsive site layouts using
    [bootstrap](http://getbootstrap.com).
- Reference bootstrap documentation.
- Add a modal to a front end project.

## Preparation

1. [Fork and clone](https://git.generalassemb.ly/ga-wdi-boston/meta/wiki/ForkAndClone)
    this repository.
1. Install dependencies with `npm install`.
1. Use `grunt serve` to start the application.

## Bootstrap

Bootstrap is the "world’s most popular front-end component library" for developing responsive, mobile first projects on the web.  It's the second most-starred project on [GitHub](https://github.com/twbs/bootstrap) according to the [Bootstrap wiki](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)).

Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. It allows you to quickly prototype your ideas or build an entire app using Sass variables and mixins; a responsive grid system; and, an extensive collection of prebuilt components and powerful plugins built on jQuery.

Checkout some of the [award-winning sites](https://www.awwwards.com/websites/bootstrap/) built on Bootstrap.

### Boostrap's Grid System

Bootstrap is built on a grid like design that consists of rows and columns, like
a table. Bootstrap utilizes a 12-column system. We can combine
different sizes of these columns to make custom grids.

![Bootstrap Grid Example](https://media.git.generalassemb.ly/user/16103/files/96713700-03a5-11e9-8eb8-9323ad08acbf)

## Lab: Review Example Pages Made With Bootstrap

In teams, closely inspect the following site list. Keeping these questions in
mind, write down your thoughts and we will discuss them together.

- [Album Example](https://getbootstrap.com/docs/4.3/examples/album/)
- [Checkout Example](https://getbootstrap.com/docs/4.3/examples/checkout/)
- [Carousel Example](https://getbootstrap.com/docs/4.3/examples/carousel/)
- [Blog Example](https://getbootstrap.com/docs/4.3/examples/blog/)

1. How is the HTML similar among the pages?

1. As you interact with the site how does the DOM change (if at all)?

1. How are elements on the pages horizontally arranged?

1. Notice any similarities among bootstrap pages in general?

1. Choose one site and draw three wireframes showing the transition of the page from mobile to tablet to desktop size.

## Bootstrap Documentation

For components and jQuery plugins always reference the [Bootstrap documentation](http://getbootstrap.com/).

Do not use premade bootstrap templates. They often have alternate versions of
jQuery or Bootstrap which are different than the versions we will be using to
practice.

## Working with the Boostrap Grid

### Containers

> Containers are the most basic layout element in Bootstrap and are **required** when using the default grid system. Choose from a responsive, fixed-width container (meaning its max-width changes at each breakpoint) or fluid-width (meaning it’s 100% wide all the time).

> While containers *can* be nested, most layouts do not require a nested container.

Use `.container` for a responsive fixed width container.

```html
<div class="container">
  ...
</div>
```

Use `.container-fluid` for a full width container, spanning the entire width of
your viewport.

```html
<div class="container-fluid">
  ...
</div>
```
### Rows

Rows are wrappers for Bootstrap columns. Each container should have **at least** one child element with the `row` class.

Columns have horizontal padding (called a gutter) for controlling the space between them. This padding is then counteracted on the rows with negative margins. This way, all the content in your columns is visually aligned down the left side.

### Columns

Bootstrap's 12-column grid system is based on elements with different `col-*`
classes. These classes are dynamic and can change to reflect the width of the
column (`1` through `12`) and at which  browser size (blank, `sm`, `md`, `lg`,
or `xl`) that column should be the defined width.

Here is a breakdown of the available classes and when we should use them:

![col-breakdown](https://media.git.generalassemb.ly/user/16103/files/8e64c780-03a4-11e9-93ac-a2ad0c72c375)

## Demo: Mobile-first Layout

Let's get some firsthand experience writing Bootstrap. Using the
documentation we discussed earlier, we can make a simple grid in the `index.html`
file located in this repo with the col-#, col-sm-#, col-md-#, and col-lg-#
classes.

## Lab: Mobile-first Layout

Now try it on your own, keeping in mind mobile-first practices.

- Make an evenly spaced 3x3 grid on mobile (small) screens or smaller
- Once this works, have your grid stay 3x3 on medium screens
- Finally, have your columns be 4x4 on large sized screens or larger

Don't forget to:

- Place your column divs within a row div.
- Place your row divs within a container div.

## Code-along: Modals and More

Modals are streamlined, but flexible dialog prompts powered by JavaScript. They
support a number of use cases from user notification to completely custom
content and feature a handful of helpful subcomponents, sizes, and more.

Bootstrap provides numerous custom JavaScript methods for us to use with modals.
It's incredibly important that we take advantage of these & use them as
directed. For example, using jQuery's `.hide` method will not work the way you
expect it to with a modal. Instead, use the preferred Bootstrap
`.modal('hide')`. Check out
[the Bootstrap docs](https://getbootstrap.com/docs/4.1/components/modal/#methods)
for further explanation.

Follow along as I add a bootstrap modal to our current sandbox page.

## Lab: Modals and More

On your own:

- Referencing the Bootstrap documentation add a form to your
    modal.
- Using your knowledge of get-form-fields write a function so that when "save changes"
    is clicked the input in the input field is console logged in Chrome.
- Referencing the Bootstrap documentation add a navbar to your page.
- Move the button that opens up the modal to the navbar.

## Useful Resources

- [Sitepoint Sass Mixins](http://www.sitepoint.com/5-useful-sass-mixins-bootstrap/)
- [Bootstrap Grid Tricks](http://willschenk.com/bootstrap-advanced-grid-tricks/)
- [Hongkait Grid Tricks](http://www.hongkiat.com/blog/bootstrap-and-sass/)
- [Bootstrap Documentation](http://getbootstrap.com/)
- [Semantic HTML](http://stackoverflow.com/a/24765186/402618/)
- [Improve Your Markup by Extending Classes](https://coderwall.com/p/wixovg/bootstrap-without-all-the-debt)
- [Bootstrap Overview Container](https://getbootstrap.com/docs/4.1/layout/overview/#containers)

## [License](LICENSE)

1. All content is licensed under a CC­BY­NC­SA 4.0 license.
1. All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
