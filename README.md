# License Plate Detection using OpenCV and Tesseract

This project detects and recognizes vehicle license plates from images using OpenCV for image processing and Tesseract for Optical Character Recognition (OCR). It is designed to run on Google Colab.

## Features
- Detects license plates from images.
- Extracts and displays license plate numbers using Tesseract OCR.
- Identifies the Indian state based on the vehicle registration code.

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/license-plate-detection.git
    cd license-plate-detection
    ```

2. Open the project in Google Colab and run the code cells.

## Prerequisites

Ensure the following packages are installed (automatically handled in Colab):
- OpenCV
- Tesseract OCR
- Numpy

## Usage

### For Image Input
1. Upload your image to Colab.
2. Call the `extract_num_from_image` function:

```python
extract_num_from_image("car_img.png")
```

## Output
- Detected license plate number.
- Identified Indian state (if applicable).
- Annotated image with license plate and number displayed.

## Example Output
```
Detected Plate Number: KA01AB1234
State: Karnataka
```

## Notes
- Ensure license plates are clear and well-lit for better recognition accuracy.
- Use `cv2_imshow()` for image display on Google Colab.

## Contributing
Pull requests are welcome. For major changes, open an issue first to discuss what you'd like to change.

## License
This project is licensed under the MIT License.

