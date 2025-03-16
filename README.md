# numana_nb_2025

## Installation of Python on Windows

1. **Download Python:**

   - Go to the official [Python website](https://www.python.org/).
   - Click on the "Downloads" tab and select "Windows".
   - Download the latest version of Python.

2. **Run the Installer:**

   - Locate the downloaded file and run the installer.
   - Make sure to check the box that says "Add Python to PATH".
   - Click on "Install Now".

3. **Verify Installation:**

   - Open Command Prompt.
   - Type `python --version` and press Enter.
   - You should see the version of Python that you installed.

4. **Install Jupyter Notebook:**

   - Open Command Prompt.
   - Type `pip install notebook` and press Enter.
   - Once installed, type `jupyter notebook` to start the notebook server.

5. **Create a New Notebook:**
   - In the Jupyter Notebook interface, click on "New" and select "Python 3".
   - You can now start writing and running Python code in your new notebook.

## Installation of Essential Python Libraries

1. **Install Matplotlib:**

   - Open Command Prompt.
   - Type `pip install matplotlib` and press Enter.
   - This will install the Matplotlib library for creating static, animated, and interactive visualizations in Python.

2. **Install NumPy:**

   - Open Command Prompt.
   - Type `pip install numpy` and press Enter.
   - This will install the NumPy library, which is essential for numerical computations in Python.

3. **Install SymPy:**

   - Open Command Prompt.
   - Type `pip install sympy` and press Enter.
   - This will install the SymPy library for symbolic mathematics in Python.

4. **Install Other Essential Libraries:**

   - Open Command Prompt.
   - Type `pip install pandas scipy scikit-learn IPython` and press Enter.
   - This will install Pandas for data manipulation and analysis, SciPy for scientific and technical computing, and Scikit-learn for machine learning.

5. **Verify Installation:**
   - Open a Python interpreter by typing `python` in Command Prompt and pressing Enter.
   - Try importing the libraries by typing:
     ```python
     import matplotlib
     import numpy
     import sympy
     import pandas
     import scipy
     import sklearn
     ```
   - If no errors are shown, the libraries have been installed successfully.

## Using Google Colab with Jupyter Notebook

1. **Open Google Colab:**

   - Go to [Google Colab](https://colab.research.google.com/).
   - You may need to sign in with your Google account.

2. **Create a New Notebook:**

   - Click on "File" in the top-left corner.
   - Select "New notebook" from the dropdown menu.
   - A new Jupyter notebook interface will open in your browser.

3. **Upload a Notebook from Your Local Machine:**

   - Click on "File" in the top-left corner.
   - Select "Upload notebook" from the dropdown menu.
   - Choose the `.ipynb` file from your local machine that you want to upload.

4. **Save Your Notebook to Google Drive:**

   - Click on "File" in the top-left corner.
   - Select "Save a copy in Drive" to save the notebook to your Google Drive for easy access later.

5. **Install Additional Libraries:**

   - You can install additional Python libraries by using the `!pip install` command in a code cell. For example:
     ```python
     !pip install matplotlib numpy sympy pandas scipy scikit-learn
     ```

6. **Run Your Code:**

   - Write and execute your Python code in the code cells.
   - You can use the same commands and libraries as you would in a local Jupyter notebook.

7. **Download Your Notebook:**
   - Click on "File" in the top-left corner.
   - Select "Download .ipynb" to download the notebook to your local machine.

Using Google Colab allows you to leverage powerful cloud-based resources for running your Jupyter notebooks, making it a convenient option for working on projects that require significant computational power.
