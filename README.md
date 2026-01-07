# ASCII-Art-
A Python project that converts images into ASCII art using only core programming logic such as loops, conditionals, and file handling—without using any external libraries.
## Project Purpose
The purpose of this project is to demonstrate how images can be represented as **ASCII art** using only **core Python programming concepts**.  
Instead of relying on external image-processing libraries, this project focuses on logic building by converting pixel brightness into ASCII characters using loops, conditional statements, and basic mathematics.

This project is ideal for:
- Learning Python fundamentals  
- Academic assignments and minor projects  
- Understanding how visual data can be represented using text  

---

## How the Code Works
The program converts an image into ASCII art through the following steps:

1. **Read the image file**  
   The image file is opened in binary mode so that raw pixel data can be accessed directly.

2. **Extract image information**  
   The width and height of the image are read from the file header.

3. **Access pixel data**  
   The program jumps to the pixel data section of the file and handles row padding correctly.

4. **Convert pixels to grayscale**  
   Each pixel’s RGB values are converted into a single grayscale value using simple averaging.

5. **Map brightness to ASCII characters**  
   Darker pixels are mapped to dense ASCII characters, while lighter pixels are mapped to simpler characters.

6. **Remove background pixels**  
   Very bright pixels are treated as background and replaced with blank spaces.

7. **Print ASCII output**  
   The final ASCII art is printed line by line in the terminal while maintaining the image’s aspect ratio.

---

## How to Run the Program

### Step 1: Prepare the Image
- Convert your image to **BMP format**
- Place the image in the same directory as the Python file
- Update the file name in the code if needed

### Step 2: Run the Script
Make sure Python is installed, then run:
tep 3: View Output

The ASCII art will be displayed directly in the terminal

Output appearance depends on terminal size and font
Requirements
Python 3.x
No external libraries required
```bash
python ascii_art.py
