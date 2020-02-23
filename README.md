# otgviz2
Simple geo-coordinate visualizer using Leaflet.js Inspired by [OTGViz](https://github.com/NUDelta/otgviz).

## How to Use

To use, simply add a list of paths to visualize into `paths.js`.

Paths are represented as lists of coordinates. A coordinate can be represented in one of two forms:

#### List Form
```javascript
const coordinate = [latitude, longitude];
```

#### Object Form
```javascript
const coordinate = {
    latitude: latitude,
    longitude: longitude
};
```

You can also have mixed types of coordinates between or within paths.
