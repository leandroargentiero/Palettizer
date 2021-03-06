# Palettizer
A palette generation app for designers who create design systems.

<!-- ABOUT THE PROJECT -->
## About The Project

<img src="images/hero.png">

I wasn’t satisfied with any online palette making tools available and I wanted to automate the process of creating palettes for my own work, so I created ‘Palettizer’. I wrote a [Medium article](https://uxdesign.cc/color-palettes-for-design-systems-part-i-f18d7fa1cd98) about the process so you can see how I approached the problem.

When creating custom color palettes, designers chose a set of 'base' colors that they find visually complementary and pleasant to one another. Once that is done, they will generate a set of shades and tints, which is often a manual and somewhat laborious process.

Unlike other palette generation apps, Palettizer leverages CIE L*a*b color space rather than RGB to generate shades and tints to create a more consistent and usable set of tonal values.

I hope you find this tool as useful for your own design projects as I do. Please reach out with any questions or follow me on [Twitter](https://twitter.com/caoimghgin) or connect with me on [LinkedIn](https://www.linkedin.com/in/kevinrmuldoon/). 

### Built With

* [create-react-app](https://github.com/facebook/create-react-app)
* [tinycolor2](https://www.npmjs.com/package/tinycolor2)
* [color-convert](https://www.npmjs.com/package/color-convert)

### Demo

Originally showcased on codesandbox.

* [codesandbox.io](https://codesandbox.io/s/palettizer-d0fop?file=/src/App.js)