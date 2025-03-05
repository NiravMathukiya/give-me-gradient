# Give Me Gradient 🎨
Generate beautiful random gradient colors effortlessly!
## Installation
Install the package using npm:
```sh
npm i give-me-gradient
```
## Usage
Require the package in your project and generate random gradients:
```javascript
const giveMeGradient = require("give-me-gradient");
console.log(giveMeGradient("linear", 3));
```
## Parameters
The `giveMeGradient` function takes two arguments:
1. **Type** (string) - The gradient type. Example: `"linear"` or `"radial"`.
2. **Color Count** (number) - The number of colors in the gradient.
### Example Output
```js
"linear-gradient(to right, #ff5733, #33ff57, #3357ff)";
```
## License
MIT © 2025 Your Name
