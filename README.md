![npm](https://img.shields.io/npm/v/d3-arrows)

# d3-arrows

## Helper functions for making curved labels for d3 svg graphics

## Installing

If you use NPM, `npm install d3-arrows`

## Usage

d3-arrows exports a function called **addLabel**. This takes a single argument which is an object with all your label options. **el** should be a d3 selector for the element you want to add the label to. Currently only one type of arrow is supported, the arc.

The **radius**, **largeArcFlag** and **sweepFlag** properties are optional. 

```js
addLabel({"el":svg,
			"id":"denison",
			"targetX":projection([151.2,-33.9])[0],
			"targetY":projection([151.2,-33.9])[1],
			"sourceX":projection([154.21,-36.09])[0],
			"sourceY":projection([154.21,-36.09])[1],
			"text":"Fort Denison"
			});
```
