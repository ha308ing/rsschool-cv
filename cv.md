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

### Education

### English
