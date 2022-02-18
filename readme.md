## Window.js
----
There's a lot coming with this code base, I just have to actually write it all.
----

- Window resizing
- Window Element API
    - Buttons
    - Select
    - Text/Password
    - Etc.
- GUI Editor

![Initial Screenshot](https://lh3.googleusercontent.com/v7BoUFXsUCu0gQdb3ckGhIlhReA0rBs_iAqP1neFJmFv6hpB3jJIigAD8JqF941ORnfUpN6eJoeRHb1xGOszxpKL1Pr2OBIttIWXdNyOZr2cKsJngYL9rD53zGOTBrFpvruUBBjVyw=w2400)

```javascript
let winjs = new WindowJS();
let windowOne = winjs.newWindow("Title", x, y, width, height);
document.body.appendChild(windowOne.windowElement);
```