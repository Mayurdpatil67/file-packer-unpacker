# File Packer Unpacker

## Overview
File Packer Unpacker is a simple Java-based tool that allows users to pack multiple files from a specified directory into a single packed file and later unpack the files back to their original form.

## Features
- **File Packing**: Combines multiple files into a single packed file, preserving their original names and sizes.
- **File Unpacking**: Extracts files from the packed file and restores them to their original form.
- **User-Friendly Console Interface**: Simple text-based prompts for easy user interaction.
- **Efficient Storage**: Files are packed with headers containing metadata for smooth unpacking.

## Prerequisites
- Java Development Kit (JDK) installed (Java 8 or later).
- Basic knowledge of command-line operations.

## Usage
### Packing Files
1. Compile the `Program327.java` file:
   ```sh
   javac Program327.java
   ```
2. Run the program:
   ```sh
   java Program327
   ```
3. Follow the prompts:
   - Enter the directory containing the files you want to pack.
   - Provide a name for the packed file.
4. The packed file will be created in the current directory.

### Unpacking Files
1. Compile the `Program355.java` file:
   ```sh
   javac Program355.java
   ```
2. Run the program:
   ```sh
   java Program355
   ```
3. Enter the name of the packed file you want to unpack.
4. The files will be extracted successfully in the current directory.

## File Structure
```
MarvellousPackerUnpacker/
├── Program327.java  # Packer implementation
├── Program355.java  # Unpacker implementation
├── README.md        # Documentation
```

## Important Notes
- Ensure that the directory provided for packing contains readable files.
- The unpacker extracts files in the same directory where the packed file is located.
- The packed file format includes a header containing filenames and sizes for accurate extraction.


