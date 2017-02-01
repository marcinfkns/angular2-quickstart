# angular2-quickstart
Simple template for Angular2. The app is built with gulp and webpack in different configurations (dev, build, dist).

## Building
```
npm run clear
npm install
```

- ```gulp build``` all source files translated and bundled
- ```gulp dist``` as above + minification
- ```gulp dev``` run local http server with hot reload

## Running
After ```gulp build``` or ```gulp dist``` open the index.html under the build/ or dist/ directory

Or

Run ```gulp dev``` and direct your browser to http://localhost:8081/index.html

## Debugging
The original Typescript source files should be displayed thanks to source mapping even after minification
