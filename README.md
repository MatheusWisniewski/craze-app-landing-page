# Craze Mobile App Landing Page
Simple landing page made with NPM, Gulp, SASS &amp; more

# Install Instructions

1. Clone this repo

2. Make sure you have these installed:

    - [node.js](http://nodejs.org/)

    - [git](http://git-scm.com)

    - [gulp](http://gulpjs.com)
    
3. Run `npm install` to install dependencies


# Development Instructions

1. Run `gulp` to created a development server on _localhost:3000_

    - Every time you save a file, the page will reload automatically

2. Run `gulp production` to create minified versions of **html**, **css** and **js** files on the **app/** folder


# Craze-carousel Componenent

To use the **craze-carousel** component in other apps, all you need to do is:

1. Create an element where the carousel will be set (example: an element with an id ```myCarousel```)

2. Populate it with direct children that will cycle using the class **craze-carousel-item** in each of them

3. Initialize the **craze-carousel** with the code:

```js
$("#myCarousel").crazeCarousel()
```

4. Enjoy!

# Pictures

Craze App is fully responsive!

1. Phone

![Phone](https://raw.githubusercontent.com/MatheusWisniewski/craze-app-landing-page/development/readme-assets/phone.png)

2. Tablet

![Tablet](https://raw.githubusercontent.com/MatheusWisniewski/craze-app-landing-page/development/readme-assets/tablet.png)

3. Desktop

![Desktop](https://raw.githubusercontent.com/MatheusWisniewski/craze-app-landing-page/development/readme-assets/desktop.png)