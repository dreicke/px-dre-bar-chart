px-simple-area-chart

## Overview

px-simple-area-chart is a Predix UI component

## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

## Getting Started

First, install the component via bower on the command line.

```
bower install px-simple-area-chart --save
```

Second, import the component to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-simple-area-chart/px-simple-area-chart.html"/>
```

Finally, use the component in your application:

```
<px-simple-area-chart
          prevent-resize="[[props.preventResize.value]]"
          width="[[props.width.value]]"
          height="[[props.height.value]]"
          x-axis-type="[[props.xAxisType.value]]"
          chart-data="[[props.chartData.value]]"
          series-config="[[props.seriesConfig.value]]"
          >
        </px-simple-area-chart>
```

<br />
<hr />

## Documentation

Read the full API and view the demo [here](https://predixdev.github.io/px-simple-area-chart).

The documentation in this repository is supplemental to the official Predix documentation, which is continuously updated and maintained by the Predix documentation team. Go to [http://predix.io](http://predix.io)  to see the official Predix documentation.


## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-simple-area-chart/issues) to submit any bugs you might find.
