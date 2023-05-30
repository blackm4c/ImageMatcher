# Python Image

A Python program to find exact matches of submit images using image similarity algorithms.

## Description

This project provides a Python program that compares a submitted image with a list of images to find the exact matches based on their content. It utilizes the Structural Similarity Index (SSIM) or Mean Squared Error (MSE) algorithm to measure the similarity between images.

## Features

- **Exact Image Match:** Find an exact match of a submitted image from a list of images.
- **Similar Image Match:** Discover similar images based on content similarity using a submitted image.
- **Flexible Input:** Accepts image files in various formats (JPEG, PNG, etc.).
- **Simple and Intuitive:** Easy-to-use interface with clear instructions.
- **Fast and Efficient:** Utilizes optimized algorithms for efficient image comparison.
- **Modular and Extensible:** Can be extended with additional image similarity algorithms or custom functionalities.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/project-name.git ```

2. Change to the project directory:

    ```bash 
    cd project-name
    ```
3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```
## Usage
1. Place your image files in the project directory or specify their paths.

### Exact Match
To find an exact match of a submit images:

1. Run the `exact_match.py` script:

    ```Python
    python3 exact_match.py
    ```
2. Enter the number of images
3. Enter the path to the image list file when prompted. The image list file should contain the paths of the images you want to compare against, with each path on a new line.
4. Enter the path to the submit image file when prompted. The program will search for an exact match of the submit image in the image list and display the result.

### Similar Match
To find similar images using a submit images:

1. Run the `similar_match.py` script:
    ```Python
    python3 similar_match.py
    ```
2. Enter the number of images
3. Enter the path to the image list file when prompted. The image list file should contain the paths of the images you want to compare against, with each path on a new line.
4. Enter the path to the submit image file when prompted.The program will compare the submit image with the images in the list and display the best match or a list of similar images found.

Make sure to provide the correct paths to the image list file and the submit image file for accurate results.

Feel free to customize the prompts and instructions according to your specific implementation.

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## Author
* Nelson - nelsonofficialmail@gmail.com

## Acknowledgments
* The `compare_ssim` function is sourced from the **scikit-image** library [(https://scikit-image.org/)](https://scikit-image.org/)