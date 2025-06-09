# AIGIRLAGENTimageconverter
A user-friendly desktop application for batch image conversion and resizing, built with Python and CustomTkinter. A simple GUI tool to batch convert, crop, and resize images to popular aspect ratios and formats.

**AIGIRLAGENT Image Converter**

A stylish and user-friendly desktop application for batch converting and resizing images. Built with Python and CustomTkinter, this tool is packaged as a standalone .exe, requiring no Python installation for end-users.
![image](https://github.com/user-attachments/assets/b3dd6a0a-990d-489c-8cca-570b97ea0a34)

**Features**

➔User-Friendly Interface: A modern, "glassmorphism" style GUI that's intuitive to use.

➔Multi-File Selection: Select one or multiple images at once using standard controls (Ctrl+Click, Shift+Click, Ctrl+A).

➔Aspect Ratio Cropping: Automatically crop images to fit standard aspect ratios:

1) 16:9 (Widescreen)
2) 9:16 (Vertical/Story)
3) 1:1 (Square)
4) 4:5 (Portrait)
5) Favicon Support: A special one-click option to create a 32x32 .ico favicon.

Multiple Output Formats: Save your converted images as:
1) JPG
2) PNG
3) WEBP
4) ICO

➔Standalone Application: Packaged with PyInstaller into a single .exe file that runs on Windows without any dependencies.




**A)** **How to Use (For Non Developers and End-Users)**

➔No installation needed!

➔Go to the Releases Page of this repository.

➔Under the latest release, find the "Assets" section.

➔Download the imageprocess.exe file.

➔Double-click the downloaded file to run the application!
(Note: Your browser or Windows may show a security warning because the app is not from a major publisher. This is normal. You can safely choose to "Keep" and "Run anyway".)




**B)** **How to Run from Source (For Developers)**

If you want to run or modify the Python script directly:

**1.** Clone the repository:


git clone https://github.com/AIGIRLAGENT/AIGIRLAGENTimageconverter.git

cd AIGIRLAGENTimageconverter

**2.** Set up a virtual environment (recommended):

python -m venv venv

venv\Scripts\activate  # On Windows
source venv/bin/activate , On macOS/Linux

**3.** Install the required libraries:
pip install customtkinter pillow

**4.** Run the script:
python imageprocess.py
