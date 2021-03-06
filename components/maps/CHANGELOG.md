<!-- markdownlint-disable MD010 -->

<!-- markdownlint-disable MD030 -->

<!-- markdownlint-disable MD004 -->

# Changelog

## [Unreleased]

## 18.1.44 (2020-04-14)

### Maps

#### Bug Fixes

- `#268755` - `isShapeSelected` property is exposed to check whether the shape is selected or not on the map.

## 18.1.42 (2020-04-01)

### Maps

#### New Features

- `#264809` - Latitude and longitude values are exposed in the arguments of panning event of the Maps control.

#### Bug Fixes

- `#268354` - `shapeDataPath` property will now work properly in the Maps control.
- `#263976` - Data label template will render properly now in the sublayers.

## 18.1.36-beta (2020-03-19)

### Maps

#### New Features

- `#F149168` - Support is provided to parse and utilize the complex data source.
- `#258888` - The map rendered from the providers such as Bing, OSM, and Google can now be exported in the supported formats.

#### Bug Fixes

- `#264141` - Zooming with `zoomToCoordinates()` method will now render the data labels properly.
- `#263976` - Script errors will not be thrown when zooming to the maximum level in the Maps component.

## 17.4.51 (2020-02-25)

### Maps

#### Bug Fixes

- `#244109` - Maps will now be aligned vertically at middle while using the `zoomToCoordinates()` method.
- `#263976` - Data labels will now be rendered properly in the correct positions.
- `#264153` - Data labels will now be rendered properly when zooming.

## 17.4.50 (2020-02-18)

### Maps

#### Bug Fixes

- `#264141`  - The data labels will now be rendered properly while using `zoomToCoordinates()` method.

## 17.4.49 (2020-02-11)

### Maps

#### Bug Fixes

- `#263056` - Now, Legend will be rendered properly when the OSM map is used along with a geometric sublayers.

## 17.4.47 (2020-02-05)

### Maps

#### Bug Fixes

- `#244109`  - Zooming will not be maintained properly when the sublayers are added to the Maps control.

## 17.4.46 (2020-01-30)

### Maps

#### New Features

- `#256121`  - Provided support to toggle the panning functionality in maps control by using the `enablePanning` property.

## 17.4.43 (2020-01-14)

### Maps

#### New Features

- `#244109`  - `zoomToCoordinates` method is now exposed to zoom the map based on the coordinates.

#### Bug Fixes

- `#244109`  - Panning is working properly now when we enable the `shouldZoomInitially` property.
- `#259807`  - Console error will not be thrown now when changing the position of the legend.
- `#259807`  - Shapes in the maps will not be cropped when changing the position of the legend after clicking the zoom reset button.
- `#258541`  - The latitude and the longitude values of the markers can now be set as a string.
- `#258541`  - The performance of the data label for point shape is now improved.

## 17.4.41 (2020-01-07)

### Maps

#### Bug Fixes

- `#258541` - Local storage is now maintained properly without clearing the user data.
- `#258541` - The performance of the marker template rendering is improved.

## 17.4.40 (2019-12-24)

### Maps

#### Bug Fixes

- `#I256861` - Now, the data labels are displaying properly for the point type sublayers.

## 17.4.39 (2019-12-17)

### Maps

#### New Features

- `#I244108`, `#I240060`, `#I247767`, `#I250088` - Provided support to zoom the maps initially, based on the marker’s location.

- `#I248021` - Provided support to cluster and expand markers with the same latitude and longitude values.

- `#I253516` - Provided clustering support for marker templates.

- `#I255189` - Improved the `markerClusterClick` event to get the hidden cluster collection details.

- `#I242130` - Provided support to select or deselect the shapes dynamically and on initial rendering.

- `#I248172` - Provided support to show tooltip on tap/click.

- `F146103`, `F147309` - Provided support to bind the shapes and colors to the markers from the data source.

## 17.3.21 (2019-10-30)

### Maps

#### New Features

- Improved the marker cluster appearance for duplicate markers.

## 17.3.14 (2019-10-03)

### Maps

#### Bug Fixes

- `F147309` - Issue in adding sub layer in the 'OpenStreetMap' has been resolved.

## 17.3.9-beta (2019-09-20)

### Maps

#### New Features

- The toggle option has been provided for legend. So, if you toggle the legend, the given color will be changed to the corresponding shape item.

## 17.2.41 (2019-08-14)

### Maps

#### Bug Fixes

- `#244108` - The issue with legend border that does not disappear when hover over the legend item has been fixed.
- The issue with tooltip was not working in Internet Explorer 11 browser has been fixed.

## 17.2.40 (2019-08-06)

### Maps

#### Bug Fixes

- `#I243271` - The issue with changing text in our component when the text argument is changed in the datalabelRendering event has been fixed.
- `#I243499` - The issue with arrow option in the navigation line has been fixed.
- `#I238404` - The issue with bubble color and size when using point type shape data has been fixed.

## 17.2.39 (2019-07-30)

### Maps

#### Bug Fixes

- `#I240804` - The issue with dynamically updating the zoom factor along with the initial case of the zoom factor  has been fixed.

- `#I240836` - The issue with border that was not applied for marker highlight and selection has been fixed.

## 17.2.36 (2019-07-24)

### Maps

#### Bug Fixes

- `#I240833` - Some labels disappear when you change "colorMapping" and refresh the map issue has been fixed
- `I240804` - The issue with dynamically updating the zoom factor has been fixed
- `I241873` - The issue with zooming the map component with a single click has been fixed

## 17.2.35 (2019-07-17)

### Maps

#### Bug Fixes

- `#I240835` - Highlight border thickness on the shape is huge when hovering on the legend item, it does not set as we given in code issue has been fixed
- `#I240836` - Marker highlight and selection settings do not make a difference issue has been fixed
- `#I240834` - Interactive legend is not working while changing data source issue has been fixed.

## 17.2.34 (2019-07-11)

### Maps

#### Bug Fixes

- `#F143717` - Zooming toolbar position misalign problem that occurs when there are multiple elements in DOM has been fixed
- `#I238404` - The issue that occurs when rendering bubble for point type Shape Data has been fixed
- `#I238839` - The console error that occurs when mouse leaves from the maps Shapes with legend hide option has been resolved

## 17.1.32-beta (2019-03-13)

### Maps

#### Bug Fixes

- Now, the border style is applied properly to the shapes when performing selection.

## 16.4.55 (2019-02-27)

### Maps

#### Bug Fixes

- Changed the OSM and Bing maps URL from http to https.

## 16.4.53 (2019-02-13)

### Maps

#### Bug Fixes

- Padding issue for OSM type layers resolved now.

## 16.4.40-beta (2018-12-10)

### Maps

#### New Features

- Support has been added for desaturation color mapping.
- Support has been added to hide specific legend items and bind legend text from data source.
- Support has been added for highlighting or selecting the legend items along with shapes.
- Support has been added to specify multiple fields in the data source for **shapePropertyPath**.
- Events has been added for zoom-in and zoom-out.

## 16.3.33 (2018-11-20)

### Maps

#### Bug Fixes

- Now map is rendering properly in universal applications
- Now panning works properly without freezing

## 16.3.22 (2018-09-25)

### Maps

#### Bug Fixes

- Now the data labels are rendering properly with numeric values.

## 16.3.17 (2018-09-12)

### Maps

#### Breaking Changes

- The maps tooltip has been replaced with `EJ2 SVG Tooltip`, so now it is mandatory to include `ej2-svg-base.umd.min.js` in system.js configuration if you are using system.js module loader. Update the system.js configuration while using this version and above.

#### Bug Fixes

- Tooltip is now working properly for marker in OSM map.

## 16.2.49 (2018-08-21)

### Maps

#### Bug Fixes

- Shape selection is now working fine with touch events

## 16.2.45 (2018-07-17)

### Maps

#### Bug Fixes

- Marker click event is now working fine with OSM layer

## 16.2.44 (2018-07-10)

### Maps

#### Bug Fixes

- Bing map type is changed as AerialWithLabels and now it is rendering properly with labels.

## 16.2.41 (2018-06-25)

### Maps

#### New Features

- Support has been added for animating the shapes on zooming.
- Support has been added to trim the maps title, when it exceeds the available width.
- Support had been provided for printing and exporting the maps.
- Support has been provided for printing.

## 16.1.24 (2018-02-22)

### Maps

The Maps control is used to visualize the geographical data. It is used to represent the statistical data of a particular geographical area on Earth, with user interactivity and provides various customizing options. All the map elements are rendered using Scalable Vector Graphics (SVG).

- **Layers** - Map is maintained through layers and it can accommodate one or more layers.
- **GeoJSON Data Input** - Supports GeoJSON data, which allows you to plot your own shapes in the maps.
- **Map Providers** - Supports map providers such as Bing and OpenStreetMap that can be added to any layers.
- **Projection** - Supports 6 types of map projections.
- **Marker** - Supports 10 types of marker shapes and also takes custom HTML element.
- **Bubbles** - Supports 2 types of bubbles such as Circle and Square.
- **Legend** - Supports legend which is useful in providing additional information about shapes, bubbles and markers with paging and customization options.
- **Data Labels** - Supports data label to provide additional information about the shapes.
- **Navigation Lines** - Lines can be rendered between various points in map.
- **Annotations** - Supports placing any HTML element on desired location in the map.
- **User interaction** - Supports interactive features like zooming, panning, tooltip, highlight, selection and interactive legend.