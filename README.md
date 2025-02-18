# Secure-Data-Hiding-in-Image-using-Steganography

## Introduction  
This project implements image-based steganography using the Least Significant Bit (LSB) technique. It allows users to hide and retrieve secret messages within image files, providing a covert method of communication. The application is built using Python and Tkinter for the GUI.

## Features  
- **Image Steganography**: Hide text data within an image using LSB encoding.  
- **Secure Access**: Uses a secret key for encryption and retrieval of data.  
- **User-Friendly Interface**: Simple GUI for easy image selection, text entry, hiding, and retrieval.  
- **Supports PNG & JPG Formats**: Works with widely used image formats.  
- **Image Preview & Save Functionality**: Allows users to view the modified image and save it.  

## Technologies Used  
- **Python**  
- **Tkinter** (for GUI)  
- **PIL (Pillow)** (for image processing)  
- **Stegano Library** (for LSB steganography)  

## Installation  

### Prerequisites  
Ensure you have Python installed (>=3.7). Install required dependencies using:  

```bash
pip install pillow stegano
```

## Usage  

1. **Run the application**  
   ```bash
   python Capstone\ Project.py
   ```

2. **Steps to Hide Data:**  
   - Click "Open Image" and select an image.  
   - Enter the secret key (default: `1234`).  
   - Type the message to hide.  
   - Click "Hide Data" and then "Save Image".  

3. **Steps to Reveal Data:**  
   - Open the modified image.  
   - Enter the correct secret key.  
   - Click "Show Data" to extract and display the hidden message.  

## Future Scope  
- Support for additional encryption layers.  
- Expand to other file formats (e.g., GIF, BMP).  
- Develop a mobile version.  

## Author  
Krishna Karthik Eluripati  
