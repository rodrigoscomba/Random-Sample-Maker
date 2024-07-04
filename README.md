# Random Sample Maker
Random Sample Maker (RSM) is a tool designed to help users create a balanced subset of images from a larger, potentially unbalanced dataset. It automates the process of selecting a fixed number of images from each category within the dataset, ensuring that the resulting subset is more evenly distributed across categories.

** **

**<ins>Key Features:</ins>**

Automated Image Selection: RSM randomly selects a specified number of images from each category, reducing manual effort and the risk of human bias.

Cross-Platform Compatibility: RSM uses cross-platform libraries compatible with Windows, Linux, and macOS.

User Interface Options: Users can define various options, such as keeping or deleting original images, ignoring folder structures, and selecting output image types and sizes.

** **

**<ins>Requirements:</ins>**

**Dependencies:** 

Python 3+, Pillow, openpyxl, and tkinter libraries.

**Dataset Structure:** 

The dataset must be organized in a hierarchical folder structure, with one root folder containing nested subfolders representing unique categories.

**Supported Image Types:** 

.png, .jpg, .jpeg, .gif, .bmp, and .tiff.

** **

**<ins>Usage:</ins>**

**UI Options:** 

Through its user interface, RSM allows users to:

Delete or keep original images.

Maintain or ignore existing folder structures.

Duplicate images for underrepresented classes.

Select output image types and sizes.

Define the number of images to copy from each category.

Generate an output Excel file detailing the new dataset's structure.

**Error Handling:**

RSM includes error-checking mechanisms to ensure correct folder selection and input formats, displaying alerts for invalid entries or conflicting options.

**Downloading:**

Users can download RSM as a .py file from this GitHub repository.

**Running:**

The program can be run on any terminal using the following command inside the folder where the file is located.

```bash
python randomsamplemaker.py
