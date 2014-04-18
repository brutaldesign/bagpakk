Bagpakk
=======

A minimal front-end CSS framework.

[View project page](http://brutaldesign.github.io/bagpakk)

##What is Bagpakk?

Bagpakk is a minimal lightweight front-end framework.

Unlike huge CSS frameworks like twitter bootstrap or foundation, Bagpakk offers a minimal scaffold to build your web application.

1. **Wordpress Ready** : The WP version of bagpakk comes with all wordpress default classes
1. **Responsive** : Fits to any devices using Progressive Enhancement
1. **Developper Friendly** : Build for developper with a simple & readable SCSS structure

##Features

+ typography
+ main container classes
+ grid system
+ buttons
+ form
+ fluid video wrapper
+ media queries
+ useful scss mixins and functions

##SCSS Usage

1. Paste the content of the bagpakk SCSS folder into your web app SCSS folder
2. Rename the bagpakk.scss file or bagpakk-wordpress.scss file with an underscore: `_bagpakk.scss`
3. Import the bagpakk SCSS file into your main project stylsheet
4. Edit the `_settings.scss` file variables if needed to change the accent color, fonts, mobile break points etc...
5. Now you can extend your CSS selectors from any bagpakk class and use all mixins and functions

```CSS
// Make sure the charset is set appropriately
@charset "UTF-8";

// Import bagpakk
@import "bagpakk";

// Example
#my-container{
	@extend .container;
	background:black(0.3); // black rgba mixin
}
```

