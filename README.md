shivs-angular-painter
======================

Angular4 component to paint on a canvas on desktop or touch devices

## Usage
1. `npm install shivs-angular4-painter`

#### canvas-painter
```html
<canvas-painter canvasWidth="600" canvasHeight="600" color="#00FF00"></canvas-painter>
```

##### Options

```javascript
{
  canvasWidth: 600, //px
  canvasHeight: 600, //px
  color: '#000',
  lineWidth: 10, //px
  cacheSize: 10 // boolean or a number of versions to keep in memory
}
```

## Drawing algorithm
Special thanks to pwambach (https://github.com/pwambach/angular-canvas-painter) and his work with the Angular1 directive. This was written to work with Angular4 because we needed it to work in our application that is written with Angular4. 


## License
MIT