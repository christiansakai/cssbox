# CSS Box

As a fullstack developer, I don't have time to continuously upgrade my CSS skills. I do learn what's new on CSS in terms of features, architectures, technique etc maybe once a year.

This repo is just a reference example for me on useful CSS features. I got most of these from following CSS tutorials. I hope to update this whenever I please.

There are two main sections in this repo:

1. CSS playground

   A quick NodeJS server to play around with CSS. Located in the root of this repo.

2. Examples

   I put finished CSS tutorials that I tried over the years in this section. Located in the `examples` folder.

   * Trillo

	 Covering Flexbox concepts. Taken from [Advanced CSS and SASS][1]
 
   * Nexter

      Covering CSS Grid concepts. Taken from [Advanced CSS and SASS][1]

# CSS Best Practices

* Try to think responsive from the beginning

* Use CSS Grid for 2D layout and Flexbox for 1D layout

* Use CSS grid for layout first approach and Flexbox for content first approach 

* If you use CSS variables, you can modify it using JS during runtime. Otherwise, use SASS variables

* Instead of font icons, consider creating your own SVG sprite using [Icomoon][2]

* When choosing fonts, choose fonts which have many font weights because those are usually designed better

* Use BEM convention for CSS naming

* For paragraph, a width range between `20 rem` to `35 rem` usually gives between `45` to `75` characters per line

[1]: https://www.udemy.com/advanced-css-and-sass/
[2]: https://icomoon.io/
