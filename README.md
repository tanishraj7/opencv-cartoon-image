# opencv-cartoon-image
This project focuses on creating a cartoon-style transformation for images using OpenCV. The pipeline combines various image processing techniques to deliver refined outputs with a unique artistic effect. Below is a detailed breakdown of the process.

## Features
- **Downscaling and Bilateral Filtering:** Achieves a cartoon-like aesthetic by reducing noise and smoothing image colors.
- **Grayscale Conversion and Blurring:** Enhances boundary details by isolating edges through median blur filters.
- **Edge Detection with Adaptive Thresholding:** Identifies prominent edges for a sketch pen effect, enabling sharp outlines.
- **Layer Integration:** Combines processed images to create the final cartoon-styled output.

## Technologies Used
- **OpenCV:** For advanced image processing and manipulation.
- **Python:** Programming language for developing the pipeline.

## Steps in the Pipeline
1. **Image Downscaling:** Reduces image resolution to simplify details.
2. **Bilateral Filtering:** Smoothens the image while preserving edges for a cartoon-like texture.
3. **Grayscale Conversion:** Converts the original image to grayscale to isolate intensity values.
4. **Median Blurring:** Softens boundaries without affecting color interference.
5. **Edge Detection:** Applies adaptive thresholding to highlight edges, creating a hand-drawn sketch effect.
6. **Image Compilation:** Merges processed layers for a polished cartoon-style result.

## Getting Started
### Prerequisites
- Python 3.7 or later
- OpenCV library (`pip install opencv-python`)

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd cartoon-style-pipeline
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Place your input image in the `input` folder.
2. Run the pipeline script:
   ```bash
   python cartoon_pipeline.py --input input/image.jpg --output output/cartoon_image.jpg
   ```
3. The transformed image will be saved in the `output` folder.

## Example
![Screenshot 2024-12-23 213342](https://github.com/user-attachments/assets/618747d9-1eb9-4840-9be5-6c9421528a4a)

