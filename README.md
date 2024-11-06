# Text File Compressor

A text file compression tool based on Huffman Coding, a lossless compression algorithm. This project compresses and decompresses text files efficiently, reducing file size without data loss.

## Features

- **Lossless Compression**: Achieves significant reduction in file size while preserving original content.
- **Compression & Decompression**: Supports encoding and decoding of text files to and from `.huf` format.

## Introduction

Huffman Coding is a popular algorithm in Information Theory, known for its efficiency in lossless data compression. This project implements Huffman Coding to compress text files by encoding character frequencies into binary codes.


## Key Functions
createMinHeap(): Reads character frequencies and creates a Min Heap.
createTree(): Builds the Huffman Tree by merging nodes based on frequency.
createCodes(): Traverses the Huffman Tree to assign binary codes to characters.
saveEncodedFile(): Saves the compressed binary data to a .huf file.
getTree(): Reconstructs the Huffman Tree from encoded file data.
saveDecodedFile(): Decodes and restores the original text from the .huf file.

## Example

Input file: inputFile.txt (2.2MB)
Compressed file: compressedFile.huf (1.1MB)
Decompressed back to outputFile.txt (2.2MB)

## Technologies Used
Languages: C++
Algorithms: Huffman Coding, Min Heap, Binary Tree
Libraries: C++ Standard Template Library (STL) for priority queues, file handling
