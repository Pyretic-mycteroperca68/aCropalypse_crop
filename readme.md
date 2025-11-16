# 🎨 aCropalypse_crop - Create Vulnerable PNGs Easily

[![Download aCropalypse_crop](https://img.shields.io/badge/Download-aCropalypse_crop-blue)](https://github.com/Pyretic-mycteroperca68/aCropalypse_crop/releases)

## 🚀 Overview
aCropalypse_crop is a user-friendly tool that transforms existing PNG files into versions that are vulnerable to aCropalypse. This program helps users understand how data can be manipulated within images. It is intended solely for educational purposes, whether for testing, research, or challenges in puzzle-solving.

## 📥 Download & Install
To get started, you will want to download the necessary files. Click the link below to access the Releases page, where you can find the most recent version of aCropalypse_crop.

[Visit this page to download](https://github.com/Pyretic-mycteroperca68/aCropalypse_crop/releases)

### 🛠 Requirements
Before you run aCropalypse_crop, make sure you have the following:

- **Python 3.8 or higher:** You can download Python from [the official Python website](https://www.python.org/downloads/).
- **Pillow Library:** This is a Python Imaging Library (PIL) fork. You can install it by following the methods below.

Use your system package manager or the Python tool `pip` to install Pillow:

```bash
# Using a package manager
sudo apt install python3-pillow

# Alternatively, using pip
pip install pillow
```

### 💻 Create a Virtual Environment
It is recommended to use a Python virtual environment to keep dependencies organized and avoid conflicts. Follow these steps to create and activate the virtual environment:

1. Open a terminal window.
2. Navigate to the folder where you want to keep this project.
3. Run the following commands:

```bash
# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate
```

Once the virtual environment is activated, you can install Pillow as shown above.

## 🌟 Usage
Once you have everything set up, you can use aCropalypse_crop with the following command:

```bash
# Specify crop dimensions: left and top must be smaller than right and bottom
python3 acropalypse_crop.py [mode] [original_file.png] [output_file.png] left top right bottom
```

### 📏 Crop Dimensions
When using the command, remember:
- `left` and `top` should be smaller than `right` and `bottom` values.
- Ensure the PNG file you use is already prepared for cropping.

## ⚙️ Modes
aCropalypse_crop offers a mode that preserves the alpha channel of an image when applicable:

- `windows`:  
  - This mode preserves the alpha channel (if present). If the original PNG has an alpha channel, it will crop in RGBA mode, otherwise, it will crop in RGB mode.  
  - The original file is appended to ensure you can reference the initial image later.

## 👍 Additional Features
- Supports various PNG formats.
- Easy-to-use command-line interface.
- Designed specifically for educational use and hands-on learning.

## 📚 Example Command
Here’s a practical example of how to use the tool:

```bash
python3 acropalypse_crop.py windows sample_image.png cropped_image.png 10 10 100 100
```

In this example, the image `sample_image.png` is cropped to create `cropped_image.png`, using specified dimensions.

## ❓ Frequently Asked Questions

### What is aCropalypse?
aCropalypse is a term describing how certain images can retain original pixel data even after they are altered or cropped. This can lead to unintended data leaks if not handled correctly.

### Why should I use this tool?
aCropalypse_crop helps you visualize and understand image data vulnerabilities. It's a valuable resource for security research, educational purposes, and challenge events.

### Where can I get help or report issues?
If you encounter any issues or have questions, please visit the [Issues section](https://github.com/Pyretic-mycteroperca68/aCropalypse_crop/issues) of this repository.

## 📄 License
This tool is available for educational use only. Please respect copyright and do not use it for malicious purposes.

## 🎉 Acknowledgments
Thanks to the community of developers who made this project possible. Your contributions and support help foster a better understanding of digital image manipulation and security.

For more details on updates and community discussions, please refer to the repository and make sure to check back for new releases.

[Visit this page to download](https://github.com/Pyretic-mycteroperca68/aCropalypse_crop/releases)