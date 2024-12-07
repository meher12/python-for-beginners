
## Steps to Install `python3-venv` and Create a Virtual Environment
We need to install the `python3-venv` package on your system to use the `venv` module for creating virtual environments. 

1. **Open Terminal**:
   Open your terminal application.

2. **Install `python3-venv`**:
   Run the following command to install the `python3-venv` package. You might need to use `sudo` to get the necessary permissions.

   ```sh
   sudo apt update
   sudo apt install python3.12-venv
   ```

3. **Create the Virtual Environment**:
   After installing the package, create your virtual environment again.

   ```sh
   python3 -m venv py3env
   ```

4. **Activate the Virtual Environment**:
   Activate the virtual environment.

   - **On macOS/Linux**:
     ```sh
     source py3env/bin/activate
     ```
   - **On Windows**:
     ```sh
     .\py3env\Scripts\activate
     ```

## Installing Jupyter in your virtual environment. Here are the steps:


1. **Install Jupyter**:
   Use `pip` to install Jupyter Notebook within the activated virtual environment.

   ```sh
   pip install jupyter
   ```

2. **Start Jupyter Notebook**:
   Once Jupyter is installed, you can start the Jupyter Notebook server.

   ```sh
   jupyter notebook
   ```

   This command will open Jupyter Notebook in your default web browser.

### Example Commands

**macOS/Linux**:
```sh
source py3env/bin/activate
pip install jupyter
jupyter notebook
```

**Windows**:
```sh
.\py3env\Scripts\activate
pip install jupyter
jupyter notebook
```

## Using `Shift + Tab` in Jupyter Notebook

In Jupyter Notebook, pressing `Shift + Tab` inside a function or near a variable provides useful information such as documentation, function signatures, and parameter details. Here's how it works:

1. **Function Signatures**:
   When you place your cursor inside a function call and press `Shift + Tab`, Jupyter will display the function's signature and documentation. This helps you understand what arguments the function accepts and what it does.

   ```python
   # Example
   print()
   ```

   If you place the cursor inside the parentheses of `print()` and press `Shift + Tab`, Jupyter will show the documentation for the `print` function.

2. **Parameter Details**:
   When you define your own function, `Shift + Tab` can help remind you of the parameters you need to pass to the function.

   ```python
   def my_function(param1, param2):
       return param1 + param2

   my_function()
   ```

   Placing the cursor inside `my_function()` and pressing `Shift + Tab` will display the parameter details.



