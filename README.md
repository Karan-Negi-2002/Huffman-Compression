# Huffman Compression Utility

## Overview
This project implements Huffman Coding for file compression and decompression in Java. The program reads an input file, compresses it using Huffman encoding, and saves the compressed data. It can also decompress the file back to its original form.

## Features
✅ Compress a text file using Huffman encoding.
✅ Decompress a previously compressed file.
✅ Uses Java's `FileInputStream` and `ObjectOutputStream` for efficient file handling.
✅ Implements a priority queue for Huffman tree construction.

## Usage
### **Compression**
1. Run the program.
2. Select option `1` for compression.
3. Enter the input file path (e.g., `E:\\input.txt`).
4. Enter the output file path for the compressed data (e.g., `E:\\compressed.txt`).
5. The file will be compressed and saved.

### **Decompression**
1. Run the program.
2. Select option `2` for decompression.
3. Enter the input file path (e.g., `E:\\compressed.txt`).
4. Enter the output file path for the decompressed data (e.g., `E:\\decompressed.txt`).
5. The file will be restored to its original content.

## Troubleshooting
- Ensure the file paths are correct and exist before running the program.
- Use double backslashes (`E:\\input.txt`) or forward slashes (`E:/input.txt`) for file paths in Windows.
- If the program prints "File compressed successfully!" but no output file is generated, check the exception logs.
- Ensure the program has the necessary permissions to read and write files.
- If decompression fails, verify that the compressed file is not corrupted or modified after compression.

## Screenshots
Screenshot of program execution:

![Image](https://github.com/user-attachments/assets/0d2a7044-d29e-4431-ab3f-48f6259636d6)
