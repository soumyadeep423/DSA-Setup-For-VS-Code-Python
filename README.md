# 🚀 Setup Guide for Coding Environment

Follow these steps to set up the repository locally and start coding:

## Step 1: Clone the Repository
```bash
git clone [<link>](https://github.com/soumyadeep423/DSA-Setup-For-VS-Code-Python.git)
```

## Step 2: Open the Repository in VS Code
1. Navigate to the folder where you cloned the repository.
2. Open the folder in Visual Studio Code.

## Step 3: Locate the Files
You should see the following files in the folder:

- **coding.py**
- **input.txt**
- **output.txt**

## Step 4: Update File Paths in `coding.py`
1. Open the `coding.py` file.
2. Update the file paths for `input.txt` and `output.txt` in the following lines:

```python
import sys
sys.stdin = open("<---your path--->/input.txt", "r")
sys.stdout = open("<---your path--->/output.txt", "w")
```

## Step 5: Start Coding
- Write your code in the same file: **coding.py**.

## Step 6: Use Split View in VS Code 
- Use the **Split** feature in VS Code to view all three files side by side for easier navigation.

## Step 7: Enter Inputs
1. Write the required inputs in **input.txt**.
2. Save the file (Do not Forget!)

## Step 8: Run the Code
- Execute the `coding.py` file. The output will be written to **output.txt**.

Happy Coding! 🚀

