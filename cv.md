# Ivan Arkaev

### Contacts

- Email: [ha308ing@outlook.com](mailto:ha308ing@outlookg.com)
- Phone: [+37409612312](tel:+37409612312)
- Website: [arkaev.netlify.app](https://arkaev.netlify.app)

### Summary

I develop websites and aimed to master new technologies.
I love web development and programming in general because it alllows to bring any idea to life.

### Skills

- JavaScript
	- Typescript
	- React, Redux, Redux Toolkit
- Builders
	- Vite
	- Webpack
	- Gulp
- HTML, PUG
-  CSS
	- Sass
	- postcss
- Git, GitHub

### Code

Last API I discovered was [Popover API](https://developer.mozilla.org/en-US/docs/Web/API/Popover_API), that allows easily implement modals and overlays:

```html
<button popovertarget="popoverId" id="b">Open</button>

<div id="popoverId" popover>
  <button
    id="closePopover"
    popovertarget="popoverId"
    popovertargetaction="hide"
  >
    Close
  </button>
  Bye!
</div>

<script>
  popoverId.togglePopover()
</script>

<style>
  #popoverId {
    --red: #ff1f1f;
    --pink: #ff9999;
    --color: var(--red);
    border-color: var(--color);
  }

  #popoverId::backdrop {
    background: var(--color);
    opacity: .4;
  }

  #popoverId:popover-open {
    --color: var(--pink);
    color: var(--color);
  }
</style>
```

which results in:

![](https://i.postimg.cc/X7xgCgbj/image.png)

[jsfiddle snippet](https://jsfiddle.net/sne14/ycLvw402/1/)

### Experience

#### Timber Distribution [repo](https://gitlab.com/jacarteaux1362/timber-dis-v2) [deploy](https://timber-dis.netlify.app/)

An SPA website with products gallery. Optimised for gesture and keyboard navigation.

-   meta tags are loaded with php for seo
-   navigate in products and categories with a keyboard
-   filter the products
-   optimized for mobile devices screens

![Timber Distribution Demo](https://arkaev.netlify.app/Screenshot-2024-08-29-at-20-04-00-2302_10642819024548472350.png)

---

#### Stellar Burgers [repo](https://github.com/ha308ing/stellar-burgers) [deploy](https://stellar-burgers-ha308ing.netlify.app/)

React app to assemble burgers, place orders and track order statuses.

-   started with JavaScript and React class components, transitioned to Typescript and functional components
-   redux tookit, thunks for api controller
-   react portal for modals
-   react-dnd library to interact with the constructor
-   react-router for routing, protected routes
-   websocket for orders feeds
-   ui tests with the Cypress framework
-   redux reducers, api tests with the Jest
-   mobile layout
-   deployed with netlify
-   docker image, github action to build the image

![Stellar Burgers Demo](https://arkaev.netlify.app/portfolio/stellar-burgers/stellar-burgers-demo-0.webp)

### Education

### English
