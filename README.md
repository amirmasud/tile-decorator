## tile-decorator

A JavaScript module for decoding [Mapbox vector tiles](https://github.com/mapbox/vector-tile-spec),
doing various modifications in JS and reencoding back. It can:

- add and remove specific properties in a layer (`decorateLayer`)
- merge features with the same properties and type into one, and sort geometries within one feature by proximity for better compression (`mergeLayer`)
- get all values of a specific property in a layer (`getLayerValues`)
