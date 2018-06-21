# Victor Hugo CMS Template
<!-- Markdown snippet -->
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify/restaurant-template-cms&stack=cms)

![homepage of an example restaurant website](https://s3-us-west-1.amazonaws.com/publis-brian-images/restaurant.jpg)

This is the repository for the example site featured in the [Coding Modern Websites with the JAMstack](https://www.netlify.com/blog/2017/10/06/coding-modern-websites-with-the-jamstack-part-1/) tutorial.

To install and run the example site locally, here’s what you’ll need:

## System Requirements

* [git](https://git-scm.com)
* [NodeJS](nodejs.org) 8 or greater
* [yarn](yarnpkg.com)
* [Hugo](https://gohugo.io/overview/installing/)

## Usage

Clone this repository and run:

```bash
yarn install
yarn start
```

Then visit http://localhost:3000/ - BrowserSync will automatically reload CSS or
refresh the page when stylesheets or content changes.

To build your static output to the `/dist` folder, use:

```bash
yarn build
```

## License

[MIT](LICENSE)
