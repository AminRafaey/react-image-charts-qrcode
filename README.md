# React Google QR Code
[![Version](https://img.shields.io/npm/v/react-google-qrcode.svg?style=for-the-badge&logo=appveyor)]()
[![React](https://img.shields.io/npm/dependency-version/react-google-qrcode/react.svg?style=for-the-badge&logo=appveyor)]()
[![License](https://img.shields.io/github/license/iamgutz/react-google-qrcode.svg?style=for-the-badge&logo=appveyor)]()

react-image-charts-qrcode is a React Component to generate a QR code via Image Charts API.
![screen shot](https://i.ibb.co/jhXRmBz/Screenshot-2022-08-15-at-8-29-44-PM.png)

## Installation
```
$ yarn add react-image-charts-qrcode
or
$ npm install --save react-image-charts-qrcode
```

## Usage

```
import React, { Component } from 'react';
import QRCode from 'react-image-charts-qrcode';

class App extends Component {
  render() {
    return (
        <div>
          <QRCode
            data="https://www.google.com"
            size={130}
            framed
          />
        </div>
    );
  }
}
```

### Props
|Prop| Type | Required | Description| Default
|---	|---	|--- |--- |--- |
|data| String | No | The data to encode| -
|size| Number | No | Image size in pixels (width x height). Min value: 30, Max value: 547| 130
|framed| Boolean | No |  Adds a frame to the image| false

# Demo
You want to see some examples? Go to [Online Demo](https://AminRafaey.github.io/react-image-charts-qrcode/)
