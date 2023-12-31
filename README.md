
# Object Detection in Street Images Using Detectron2

## Overview
In this project, I utilized the Detectron2 library and transfer learning techniques to train a model for detecting persons, cars, and traffic lights. The custom dataset comprises street images taken in the Haifa area, particularly around the University campus. This project serves as a testament to the effectiveness of transfer learning and the Detectron2 library for object detection tasks. It demonstrates the library's potential applicability in real-world scenarios. This work is an ongoing effort and will be further developed in Final Project 1 & 2.

Submitted by: Muhammad Haj Ali

## Installation Requirements
The project requires Python 3.9.13 and Microsoft Visual C++ 14.0. A compatible graphics card is also necessary for optimal performance.

### Steps to Install Detectron2
1. Ensure you have the correct Python version (3.9.13).
2. Install the necessary dependencies:
   ```bash
   pip install pyyaml==5.1
   pip install torch==1.8.0+cu101 torchvision==0.9.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
   pip install cython
   pip install opencv-python
   ```
3. Clone the Detectron2 repository:
   ```bash
   git clone https://github.com/facebookresearch/detectron2.git
   ```
4. Install Detectron2 from the cloned repository:
   ```bash
   cd detectron2
   pip install -e .
   ```
> **Note**: An older version of PyTorch is used since Detectron2 has not released packages for PyTorch 1.9.

If you need the data for this project, please contact me.
