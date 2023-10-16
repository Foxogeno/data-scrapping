# data-scrapping

Step 1: Download and Install Visual Studio Code

Visual Studio Code (VS Code) is a code editor that will allow you to open and run the script. Follow these steps:

Download Visual Studio Code from the official website: Visual Studio Code Download.
Run the downloaded installation file and follow the on-screen instructions to complete the installation.

Step 2: Install Python

To run the script, you'll need to have Python installed. Follow these steps:

Download the Python installer from the official Python website: Python Downloads.
Choose the latest stable version for your operating system (e.g., Windows).
Run the Python installation file, and during installation, check the "Add Python x.x to PATH" option.

Step 3: Install Git

You will need Git to clone the GitHub repository. Follow these steps:

Download Git from the official Git website: Git Downloads.
Run the Git installation file and follow the on-screen instructions.

Step 4: Clone the GitHub Repository

The code is located in a GitHub repository. Follow these steps to get a copy of the code on your computer:

Open Visual Studio Code.

Go to the "File" menu and select "Open Folder."

In the dialog window, create a folder on your computer where you want to save the code.

Open a terminal window in Visual Studio Code by clicking "Terminal" at the top and selecting "New Terminal."

In the terminal, run the following command to clone the GitHub repository:

shell
Copy code
git clone [https://github.com/yourusername/yourrepository.git](https://github.com/Foxogeno/data-scrapping.git)
Replace yourusername/yourrepository with the actual URL of the repository you want to clone.

Step 5: Install Python Libraries

To run the script, you need to install some Python libraries. In the same terminal in Visual Studio Code, run the following commands:

shell
Copy code
pip install openpyxl
pip install selenium
These commands will install the required openpyxl and selenium libraries for the code.

Step 6: Update Code Paths

You will need to update specific paths in the code:

In line 9, replace GECKO_DRIVER_PATH with the path to your GeckoDriver executable.
In lines 11, 202, 248, 253, and 256, replace EXCEL_FILENAME with the desired path where you want to save the Excel files. Make sure to specify the full path, including the file name and extension.
Step 7: Run the Code

Now that you have everything set up, you can run the code:

Open the Python file in Visual Studio Code by clicking "File" > "Open File" and selecting the downloaded Python file.
Click the "Run Python File in Terminal" icon in the upper-right corner of the editor (it looks like a triangle).
The code will run, and you will see the results in the terminal.
