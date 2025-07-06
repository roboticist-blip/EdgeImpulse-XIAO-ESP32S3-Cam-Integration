# Contribution Guide

Want to add support for another ESP32 camera board? Follow these steps:

1. Find the pin configuration for your board
2. Add a new `#elif defined(CAMERA_MODEL_YOUR_BOARD)` section in `esp32_camera_config.h`
3. Follow the existing pattern for GPIO pin definitions
4. Test the configuration with a basic camera example
5. Submit a pull request with:
   - Your configuration changes
   - A basic example (if available)
   - Documentation update

## Testing

Please test your configuration with:
- Basic camera example
- Edge Impulse image classification example
