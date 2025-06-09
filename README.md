# AIGIRLAGENTimageconverter
A user-friendly desktop application for batch image conversion and resizing, built with Python and CustomTkinter. A simple GUI tool to batch convert, crop, and resize images to popular aspect ratios and formats.

**AIGIRLAGENT Image Converter**

A stylish and user-friendly desktop application for batch converting and resizing images. Built with Python and CustomTkinter, this tool is packaged as a standalone .exe, requiring no Python installation for end-users.
![image](https://github.com/user-attachments/assets/9d34f528-8861-4a55-8e39-6b4d1e1754e9)


**Features**

➔ Modern, User-Friendly Interface: An intuitive GUI that is easy for anyone to use.

➔Batch Processing: Select and convert multiple images at once using standard controls (Ctrl+Click, Shift+Click, Ctrl+A).

➔Flexible Resizing: Aspect Ratio Cropping: Automatically crop images to fit standard aspect ratios:
      
      1) 16:9 (Widescreen)
      2) 9:16 (Vertical/Story)
      3) 1:1 (Square)
      4) 4:5 (Portrait)
      5) Favicon Support: A special one-click option to create a 32x32 .ico favicon.
  
      Crop to Fill: Automatically crops the image to perfectly fit the selected aspect ratio.
  
      Pad to Fit: Preserves the entire original image by adding white borders to fit the aspect ratio.

➔Multiple Output Formats: Convert your images to JPG, PNG, WebP, or ICO.

      1) JPG
      2) PNG
      3) WEBP
      4) ICO

➔Adjustable Quality & Compression:

    Use a slider (1-100) to control the quality and file size for JPG and WebP formats.

    PNG files are automatically optimized for the best lossless compression.

➔Real-time File Size Estimation: Get an instant estimate of the output file size as you adjust settings.

➔Powerful Filenaming:

    Keep the original filename.

    Use a custom filename for single or multiple files.

    Automatically adds sequential numbers (file-1, file-2, etc.) for bulk custom naming.

➔Standalone Application: Packaged with PyInstaller into a single .exe file that runs on Windows without any dependencies.

============================================================================================


**A)** **How to Use (For Non Developers and End-Users)**

➔No installation needed!

➔Go to the Releases Page of this repository.

➔Under the latest release, find the "Assets" section.

➔Download the imageprocess.exe file.

➔Double-click the downloaded file to run the application!
(Note: Your browser or Windows may show a security warning because the app is not from a major publisher. This is normal. You can safely choose to "Keep" and "Run anyway".)
![image](https://github.com/user-attachments/assets/6e1c4696-7d4a-4427-938a-47b571176cb3)


============================================================================================

**B)** **How to Run from Source (For Developers)**

If you want to run or modify the Python script directly:

**1.** Clone the repository:


    git clone https://github.com/AIGIRLAGENT/AIGIRLAGENTimageconverter.git

    cd AIGIRLAGENTimageconverter

**2.** Set up a virtual environment (recommended):

    python -m venv venv

    venv\Scripts\activate  # On Windows
    source venv/bin/activate # On macOS/Linux

**3.** Install the required libraries:
    
    pip install customtkinter pillow

**4.** Run the script:
    
    python imageprocess.py


**Technologies Used**

    Python 3
    CustomTkinter - For the modern graphical user interface.
    Pillow (PIL Fork) - For all image processing tasks.
    PyInstaller - To package the application into a standalone executable.
