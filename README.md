# DeOldify: Grayscale Image Colorization

This project utilizes **DeOldify**, a state-of-the-art image colorization tool, to convert grayscale images into vibrant colorized versions. Follow the steps below to set up and use the project to colorize your own images.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Information](#model-information)
- [Contributing](#contributing)
- [License](#license)

## Requirements

- Python 3.x
- Jupyter Lab
- Required Python dependencies (listed in `requirements.txt`)

## Installation

### Step 1: Clone the Repository

First, clone the DeOldify repository from GitHub:

```bash
git clone https://github.com/jantic/DeOldify
```

### Step 2: Install Dependencies

Navigate into the cloned repository and install the required dependencies using `pip`:

```bash
cd DeOldify
pip install -r requirements.txt
```

This will install all the necessary libraries to run the DeOldify colorization model.

### Step 3: Download the Pre-trained Model

Download the pre-trained model file `ColorizedArtistic_zen.pth` (or your preferred model) and place it in the `models/` folder within the DeOldify directory.

- You can download the model from [here](https://data.deepai.org/deoldify/ColorizeArtistic_gen.pth).

Move the file to the `models` folder:

```bash
mv ColorizedArtistic_zen.pth models/
```

### Step 4: Open Jupyter Lab

To run the project, open **Jupyter Lab** in the DeOldify directory:

```bash
jupyter lab
```

Once Jupyter Lab is open, navigate to and open the notebook file `ImageColorizer.ipynb`.

### Step 5: Using Custom Images

You can place your own grayscale images in the `test_images/` folder. Then, set the path to your image within the notebook and run the necessary cells to colorize it.

To colorize an image:

1. Move your image to the `test_images/` folder.
2. Set the image path in the notebook to point to your custom image, for example:
   ```python
   source_path = 'test_images/your_image.jpg'
   ```
3. Execute the cells in the notebook to generate the colorized version of your image.

## Model Information

The `ColorizedArtistic_zen.pth` model is pre-trained to colorize images in an artistic style. If you're using this model, ensure it's properly placed in the `models/` folder as instructed above.

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests.

## License

DeOldify is licensed under the MIT License. For more information, please refer to the [original repository](https://github.com/jantic/DeOldify).

