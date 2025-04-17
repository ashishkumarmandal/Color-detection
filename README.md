# Color Detection Project

A Python-based interactive color detection application that allows users to identify colors in images by simply clicking on them. This project uses OpenCV and Pandas to provide real-time color information including color names and RGB values.

## Features

- Interactive color detection through mouse clicks
- Real-time display of color names and RGB values
- Support for a wide range of colors through a comprehensive color database
- Visual feedback with color rectangles and text overlays
- Automatic text color adjustment for better visibility on light backgrounds

## Files Included

- `color_detection.py`: The main Python script for color detection
- `color_detection_final.ipynb`: Jupyter Notebook with step-by-step implementation
- `colors.csv`: Database of color names and their RGB values
- Sample images for testing

## Prerequisites

- Python 3.x
- OpenCV (cv2)
- Pandas
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashishkumarmandal/Color-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Color-detection
   ```

3. Install the required packages:
   ```bash
   pip install opencv-python pandas numpy
   ```

## Usage

### Using the Python Script

1. Run the script with an image path:
   ```bash
   python color_detection.py --image path/to/your/image.jpg
   ```

2. Once the image window opens:
   - Double-click anywhere on the image to detect the color at that point
   - The color name and RGB values will be displayed at the top of the window
   - Press 'ESC' to close the application

### Using the Jupyter Notebook

1. Open `color_detection_final.ipynb` in Jupyter Notebook
2. Follow the step-by-step implementation to understand the color detection process
3. Modify and experiment with the code as needed

## How It Works

1. The application loads a predefined color database from `colors.csv`
2. When you click on an image, it captures the RGB values at that point
3. The algorithm finds the closest matching color from the database
4. Results are displayed in real-time with visual feedback

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

- OpenCV community for the computer vision library
- Contributors to the color database
- All users who have helped improve this project
