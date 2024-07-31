
# PDF Table Extractor

## Description

PDF Table Extractor is a Python tool designed to extract table coordinates and crop tables from PDF documents. This tool processes PDF files, identifies table structures, and extracts the coordinates of the tables for further processing or analysis.It is capable of detecting multiple tables in a given PDF.

## Features

- Extracts each page of pdf as an image , processes one page at once
- Extracts table coordinates from PDF files.
- Crops and saves table images.
- Utilizes OpenCV for image processing.


## Dependencies

- PyMuPDF (fitz)
- OpenCV
- NumPy


## Credits

This project was inspired by the box detection algorithm described in the Medium article "[A Box-Detection Algorithm for Any Image Containing Boxes](https://medium.com/coinmonks/a-box-detection-algorithm-for-any-image-containing-boxes-756c15d7ed26)" by Kanan Vyas

## Acknowledgments

- The project uses PyMuPDF for PDF handling.
- OpenCV is used for image processing tasks.
