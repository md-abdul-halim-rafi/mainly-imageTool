![](https://badgen.net/badge/Editor.js/v2.0/blue)

# Image Tool

Image Block for the [Editor.js](https://editorjs.io). 
Inspired from official [package](https://github.com/editor-js/image.git)

![](https://capella.pics/63a03d04-3816-45b2-87b2-d85e556f0066.jpg)

## Features

- Uploading file from the device
- Pasting copied content from the web
- Pasting images by drag-n-drop
- Pasting files and screenshots from Clipboard
- Allows stretching an image to the container's full-width

**Notes**

This Tool requires server-side implementation for the file uploading. See [backend response format](#server-format) for more details.

This Tool is also capable of uploading & displaying video files using the <video> element. To enable this, specify video mime-types via the 'types' config param.

## Installation

### Install via NPM

Get the package

```shell
npm i --save-dev @mainly/imagetool
```

Include module at your application

```javascript
import ImageTool from "@mainly/imagetool";
```

Usage is as same as EditorJs image tool.