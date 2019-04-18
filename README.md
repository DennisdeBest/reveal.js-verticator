# reveal.js-verticator
A plugin for [Reveal.js](https://revealjs.com) that adds indicators to show the amount of slides in a vertical stack. 


Sometimes you would like to have an indication of how many slides are remaining in a vertical stack. This plugin does just that.  




## Installation

Copy the verticator folder to the plugins folder of the reveal.js folder, like this: `plugin/verticator`. Now add it to the dependencies of Reveal.js.


```javascript
Reveal.initialize({
	// ...
	dependencies: [
		// ... 
		{ src: 'js/revealjs/plugin/verticator/verticator.js' },
		// ... 
	]
});
```

Now copy the verticator.css file and make a reference to it. Note that this example has an "assets" folder for resources. You can use whatever setup for the hierarchy, as long as the references are correct :-)

```html
<link rel="stylesheet" href="assets/css/verticator.css">
```



## Like it?

If you like it, please star this repo.




## License
MIT licensed

Copyright (C) 2019 Martijn De Jongh (Martino)