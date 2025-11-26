# Python for Absolute Beginners

This repository contains Jupyter Notebook–based practice material for Python, aligned with the **“Python for Absolute Beginners”** YouTube playlist.

The first notebook walks through:

- What Python variables are
- How to create and use them
- How to print and inspect variable values
- Reassigning (updating) variable values
- Valid and invalid variable names (numbers, underscores, spaces, and case sensitivity)
- Simple examples using:
  - `my_name`
  - `birth_year`
  - `my_three_fav_fruits`

---

## Files in this repository

- `Python_Variables.ipynb`  
  Jupyter notebook used in the **Python Variables Explained (Beginner Friendly)** video.

More notebooks will be added as the playlist grows.

---

## Prerequisites

You’ll need:

- **Python** 3.9+ installed  
- **Visual Studio Code (VS Code)** installed  
- VS Code extensions:
  - **Python** (by Microsoft)
  - **Jupyter** (by Microsoft)

---

## Setup Instructions

1. **Clone this repository**

   ```bash
   git clone https://github.com/rabiyaabbasi/Python-for-Absolute-Beginners.git
   cd Python-for-Absolute-Beginners
   
2. **Create virtual environment**
bash: python -m venv .venv

3. **Activate the virtual environment**

.venv\Scripts\Activate.ps1 (bash)
source .venv/bin/activate (windows powershell)

4. **Install dependencies**

pip install -r requirements.txt

---

## Using Jupyter Notebooks in VS Code

1. **Open the folder in VS Code**

File → Open Folder…

Select the Python-for-Absolute-Beginners folder.

2. **Select the Python interpreter**

Press Ctrl+Shift+P (or Cmd+Shift+P on macOS).

Type: Python: Select Interpreter.

Choose the interpreter from your virtual environment (it should show .venv in the path).

3. **Open the notebook**

In the Explorer sidebar, open Python_Variables.ipynb.

VS Code will open it in the Notebook view.

4. **Choose a kernel**

At the top right of the notebook, click the kernel selector.

Pick the Python environment associated with .venv.

5. **Run the cells**

Click the ▶ Run icon on each cell, or use Run All from the toolbar.

You should see outputs directly under each cell (e.g. "Alex", ALEX, lists of fruits, etc.).


---
## Youtube Playlist: Python for Absolute Beginners
This repository supports the YouTube playlist: [Python for Absolute Beginners](https://www.youtube.com/watch?v=ckjfuwhQY0U&t=32s)

The notebooks here are designed so that learners can:
-->Follow along with the video step by step
--> Experiment with the examples (my_name, birth_year, my_three_fav_fruits)
--> Modify values and add their own cells to build confidence with Python

