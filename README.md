# ESP32 Camera Configuration for Edge Impulse

This repository provides camera pin configurations for various ESP32 boards to work seamlessly with Edge Impulse's computer vision projects. It extends the default configurations provided by Edge Impulse to support more boards, including the Seeed Studio XIAO ESP32S3.

## Features

- Supports 20+ ESP32 camera boards
- Plug-and-play configuration for Edge Impulse projects
- Easy to extend for new boards
- Tested with Edge Impulse's image classification models

## Supported Boards

See the full list of [supported boards](docs/supported_boards.md).

## Quick Start

1. Clone this repository or download the ZIP file
2. Copy the `esp32_camera_config` folder to your Arduino libraries folder
3. In your Edge Impulse project:
   ```cpp
   #include "esp32_camera_config.h"
   // Select your camera model
   #define CAMERA_MODEL_XIAO_ESP32S3
