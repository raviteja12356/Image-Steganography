# Image Steganography

## 📌 Project Description

Image Steganography is a C programming project that allows secret data to be hidden inside a BMP image using the Least Significant Bit (LSB) technique.

The project supports both encoding and decoding operations.

## 🚀 Features

- Encode secret data into a BMP image
- Decode hidden data from a stego image
- Hide text or file data inside an image
- Preserve the visual appearance of the image
- Validate input files and encoding capacity
- Command-line based application

## 🛠️ Technologies Used

- C Programming
- File Handling
- Pointers
- Structures
- Bitwise Operations
- Command Line Arguments
- BMP Image Format
- LSB Steganography
- GCC Compiler

## 🔐 How Steganography Works

The project uses the Least Significant Bit (LSB) of image pixel data.

A small portion of the image's pixel information is modified to store secret data.

The changes are small enough that the original image and encoded image appear visually similar.

## 📂 Project Structure

```text
Image-Steganography/
│
├── encode.c
├── decode.c
├── encode.h
├── decode.h
├── types.h
├── common.h
├── main.c
└── README.md
