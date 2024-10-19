# Seam Carving Algorithm in C++

## Introduction
This project implements the **Seam Carving** algorithm for content-aware image resizing, a technique used to resize images by removing or inserting seams—paths of least energy—vertically or horizontally. Seam carving effectively reduces or enlarges an image while preserving the important features, such as objects or regions of interest, by selectively removing pixels that have the least importance based on an energy function.

### Features:
- Resize images by removing vertical or horizontal seams.
- Energy function based on the gradient magnitude, which evaluates pixel importance.
- Supports dynamic resizing by specifying the target width and height.

## Dependencies
The project depends on the following libraries:
- **OpenCV** (for image processing and visualization)
- **C++ STL** (for basic I/O and operations)

