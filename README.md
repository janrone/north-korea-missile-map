Missile Map
===========

Generate a [D3](http://d3js.org/) spinning globe on canvas and animate it using scrollyteller waypoints.

A project generated from [aunty](http://github.com/abcnews/aunty)'s `preact-app` template.

Depends on [Odyssey Scrollyteller](https://github.com/abcnews/odyssey-scrollyteller) and [ABC's Odyssey Template](https://github.com/abcnews/odyssey).

The article is live now [on the ABC website](http://www.abc.net.au/news/2017-10-16/north-korea-missile-range-map/8880894).

## Configuration

Generate marker waypoints in CoreMedia with hashes like `#markIDnorthkoreaRANGE1000LABELguam`

Needs a JSON data file with your coordinates and names etc.

Note: this project is for use internally within the ABC. It will probably not work on its own, but you are welcome to have a look around (the most interesting code is in [/src/components/Globe.js](https://github.com/abcnews/north-korea-missile-map/blob/master/src/components/Globe.js))

A standalone working model of the globe interactive can be found [on Glitch here](https://glitch.com/edit/#!/nk?path=script.js:1:0).

## Authors

- Joshua Byrd ([phocks@gmail.com](mailto:phocks@gmail.com))
