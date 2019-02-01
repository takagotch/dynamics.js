### dynamics.js
---
https://github.com/michaelvillar/dynamics.js

```js
var el = document.getElementById("logo")
dynamics.animate(el, {
  translateX: 350,
  scale: 2,
  opacity: 0.5
}, {
  type: dynamics.sprint,
  frequency: 200,
  friction: 200,
  duration: 1500
})

var path = document.querySelector("path")
dynamics.animate(path, {
  d: "M0,0 L0,100 L100,50 L0,0 Z",
  fill: "#FF0000",
  rotateZ: 45,
  rotateCX: 100,
  rotateCY: 100
},{
  friction: 300
})

var o = {
  number: 10,
  color: "#FFFFFF",
  string: "10deg",
  array: [ 1, 10 ]
}
dynamics.animate(o, {
  number: 20,
  color: "#000000",
  string: "90deg",
  array: [-9, 99]
})
```

```
[{"x":0,"y":0,"cp":[{"x":0.2,"y":0}]},
 {"x":0.5,"y":-0.4,"cp":[{"x":0.4,"y":-0.4},{"x":0.8,"y":-0.4}]},
 {"x":1,"y":1,"cp":[{"x":0.8,"y":1}]}]
```

```
```

