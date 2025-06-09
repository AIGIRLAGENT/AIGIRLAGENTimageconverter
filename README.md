# AIGIRLAGENTimageconverter
A user-friendly desktop application for batch image conversion and resizing, built with Python and CustomTkinter. A simple GUI tool to batch convert, crop, and resize images to popular aspect ratios and formats.

AIGIRLAGENT Image Converter
A stylish and user-friendly desktop application for batch converting and resizing images. Built with Python and CustomTkinter, this tool is packaged as a standalone .exe, requiring no Python installation for end-users.
(Recommendation: Replace this placeholder URL with a real screenshot of your app!)
Features
User-Friendly Interface: A modern, "glassmorphism" style GUI that's intuitive to use.
Multi-File Selection: Select one or multiple images at once using standard controls (Ctrl+Click, Shift+Click, Ctrl+A).
Aspect Ratio Cropping: Automatically crop images to fit standard aspect ratios:
16:9 (Widescreen)
9:16 (Vertical/Story)
1:1 (Square)
4:5 (Portrait)
Favicon Support: A special one-click option to create a 32x32 .ico favicon.
Multiple Output Formats: Save your converted images as:
JPG
PNG
WEBP
ICO
Standalone Application: Packaged with PyInstaller into a single .exe file that runs on Windows without any dependencies.
How to Use (For End-Users)
No installation needed!
Go to the Releases Page of this repository.
Under the latest release, find the "Assets" section.
Download the imageprocess.exe file.
Double-click the downloaded file to run the application!
(Note: Your browser or Windows may show a security warning because the app is not from a major publisher. This is normal. You can safely choose to "Keep" and "Run anyway".)
How to Run from Source (For Developers)
If you want to run or modify the Python script directly:
Clone the repository:
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
Use code with caution.
Bash
Set up a virtual environment (recommended):
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On macOS/Linux
Use code with caution.
Bash
Install the required libraries:
pip install -r requirements.txt
Use code with caution.
Bash
(You'll need to create a requirements.txt file by running pip freeze > requirements.txt in your terminal after installing the libraries below)
pip install customtkinter
pip install pillow
Run the script:
python imageprocess.py
Use code with caution.
Bash
Building the .exe
To create the standalone executable from the source code, first install PyInstaller:
pip install pyinstaller
Use code with caution.
Bash
Then, run the following command from the project's root directory:
pyinstaller --onefile --windowed --icon="icon.ico" imageprocess.py
Use code with caution.
Bash
The final .exe will be located in the dist/ folder.
Technologies Used
Python 3
CustomTkinter - For the modern graphical user interface.
Pillow (PIL Fork) - For all image processing tasks.
PyInstaller - To package the application into an executable.
