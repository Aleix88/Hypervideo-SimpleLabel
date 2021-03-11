# Hypervideo-SimpleLabel
Simple Label plugin for [Hypervideos.js](https://github.com/Aleix88/Hypervideos)
<img src="https://github.com/Aleix88/Hypervideo-SimpleLabel/blob/main/simple_label.png?raw=true">

## Features
- Display a label when on tag hover.
- Add anchor links to the label too.
- Enable differents labels of differents tags at the same time.

## Installation
### Manual downloading
1. Download the SimpleLabel.js file.
2. Import this file in your html.

## Usage
Add this plugin to the hypervideo configuration object with the text paràmeter on config:

    const config = {
        ...

        "tags": [
          {
            ...

            "plugin": {
                "name": "SimpleLabel",
                "config": {
                    "text": "Your label text here!"
                }
            }

          }, 
          ...
        ]
      };

## Config params

| Field | Type | Description |
| ------------- | ------------- | ------------- |
| text | string | Label text value |