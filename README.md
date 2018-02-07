[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# CSS: Layout with Bootstrap

## Prequisites

-   [ga-wdi-boston/html-css-layout](https://git.generalassemb.ly/ga-wdi-boston/html-css-layout)
-   [ga-wdi-boston/html-css-sass](https://git.generalassemb.ly/ga-wdi-boston/html-css-sass)

## Objectives

By the end of this, developers should be able to:

-   Create mobile-first, responsive site layouts using
    [bootstrap](http://getbootstrap.com).
-   Reference bootstrap documentation.
-   Add a modal to a front end project.

## Preparation

1.  [Fork and clone](https://git.generalassemb.ly/ga-wdi-boston/meta/wiki/ForkAndClone)
    this repository.
1.  Install dependencies with `npm install`.

## Twitter Bootstrap

Bootstrap is a free and open-source collection of tools for creating websites
and web applications. It contains HTML- and CSS-based design templates for
typography, forms, buttons, navigation and other interface components, as
well as optional JavaScript extensions. It aims to ease the development of
dynamic websites and web applications.

"Bootstrap is the most popular HTML, CSS, and JS framework for developing
responsive, mobile first projects on the web." - bootstrap.com

Bootstrap is the most-starred project on GitHub, with over 100K stars and more
than 50K forks.

[Bootstrap Wiki](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))

Bootstrap is built on a grid like design that consists of rows and columns, like
a table. In each row, Bootstrap utilizes a 12 column system.

![Bootstrap Grid Example](https://cloud.githubusercontent.com/assets/8379295/15674757/818a4ff2-270c-11e6-8ad3-9d5825f0c188.png)

## Lab: Review Sites Made With Bootstrap

In teams, closely inspect the following site list.  Keeping these questions in
mind, write down your thoughts and we will discuss them together.

-   [Divinity in Tech](http://divinityintech.com/)
-   [UI Viking](http://uiviking.com/)
-   [MintVine](https://mintvine.com/)
-   [Pave](http://pavingtheway.net/)

1.  How are the the pages similar?

1.  How is the HTML similar among the pages?

1.  As you interact with the site how does the DOM change (if at all)?

1.  How are elements on the pages horizontally arranged?

1.  Notice any similarities among bootstrap pages in general?

## Bootstrap Documentation

For components and jQuery plugins always reference the Bootstrap docs.

 [Bootstrap Documentation](http://getbootstrap.com/)

Do not use premade bootstrap templates. They often have alternate versions of
jQuery or Bootstrap which are different than the versions we will be using to
practice.

## Demo: Mobile-first Layout

Let's get some firsthand experience writing Boootstrap.  Using the
documentation we discussed earlier, write a simple grid in the `index.html` file
located in this repo.  Make use of col-xs-#, col-sm-#, col-md-#, and col-lg-#.

## Lab: Laptop/Desktop Layout

Try making an evenly spaced 3x3 grid.

-   Place your column divs within a row div.
-   Place your row divs within a container div.
-   Experiment with various viewport sizes.

## Code-along: Modals and More

"Modals are streamlined, but flexible dialog prompts powered by JavaScript. They support a number of use cases from user notification to completely custom content and feature a handful of helpful subcomponents, sizes, and more." - Bootstrap

Bootstrap provides numerous custom Javascript methods for us to use with modals. It's incredibly important that we take advantage of these & use them as directed. For example, using jQuery's `.hide` method will not work the way you expect it to with a modal. Instead, use the preferred Bootstrap `.modal('hide')`. Check out [the Bootstrap docs](https://getbootstrap.com/docs/3.3/javascript/#modals-methods) for further explanation.

Follow along as I add a bootstrap modal to our current sandbox page.

## Lab: Modals and More

On your own:

-   Referencing the Bootstrap documentation add a form to your
    modal.
-   Using your knowledge of get-form-fields write a function so that when "save changes"
    is clicked the input in the input field is console logged in Chrome.
-   Referencing the Bootstrap documentation add a navbar to your page.
-   Move the button that opens up the modal to the navbar.

## Useful Resources

-   [Sitepoint Sass Mixins](http://www.sitepoint.com/5-useful-sass-mixins-bootstrap/)
-   [Bootstrap Grid Tricks](http://willschenk.com/bootstrap-advanced-grid-tricks/)
-   [Hongkait Grid Tricks](http://www.hongkiat.com/blog/bootstrap-and-sass/)
-   [Bootstrap Documentation](http://getbootstrap.com/)
-   [Semantic HTML](http://stackoverflow.com/a/24765186/402618/)
-   [Improve Your Markup by Extending Classes](https://coderwall.com/p/wixovg/bootstrap-without-all-the-debt)

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
