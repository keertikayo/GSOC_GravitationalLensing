# GSOC Gravitational Lensing Project

## Folder Structure

Ensure your project directory follows this structure:

```plaintext
project_root/
│── common_test/  # Download and place the common_test dataset here
│── lens-finding-test/  # Download and place the specific_test dataset here
│── node_modules/
│── package.json
│── README.md
│── requirements.txt
│── venv/
│   ├── bin/
│   ├── etc/
│   ├── include/
│   ├── lib/
│   ├── share/
│── Common_test.ipynb
│── Specific_test.ipynb
```

## Dataset Downloads

Please download the datasets from the links below and place them in the correct directories:

- **Common Test Dataset:** [Download here](https://drive.google.com/file/d/1ZEyNMEO43u3qhJAwJeBZxFBEYc_pVYZQ/view)
- **Specific Test Dataset:** [Download here](https://drive.google.com/file/d/1doUhVoq1-c9pamZVLpvjW1YRDMkKO1Q5/view?usp=drive_link)

After downloading, extract the datasets into their respective folders as shown in the folder structure.

## Project Setup and Running Jupyter Notebooks

### Setting up the Virtual Environment

This project uses a Python virtual environment (`venv`) for dependency management. Follow these steps to activate the virtual environment and run Jupyter notebooks.

### 1. Create the Virtual Environment

Navigate to your project directory and run:

#### **On macOS/Linux:**
```bash
python3 -m venv venv
```

#### **On Windows:**
```cmd
python -m venv venv
```

### 2. Activate the Virtual Environment

#### **On macOS/Linux:**
```bash
source venv/bin/activate
```

#### **On Windows (Command Prompt):**
```cmd
venv\Scripts\activate
```

#### **On Windows (PowerShell):**
```powershell
venv\Scripts\Activate.ps1
```

Once activated, you should see `(venv)` appear at the beginning of your command prompt.

### 3. Install Dependencies

If this is your first time setting up the project, install the required dependencies using:
```bash
pip install -r requirements.txt
```
Make sure the `requirements.txt` file exists in your project; otherwise, manually install the required packages.

### 4. Running Jupyter Notebook

Start Jupyter Notebook to run any `.ipynb` files:
```bash
jupyter notebook
```
This will open Jupyter in your browser, allowing you to select and run the notebooks stored in the project.

---

## Deactivating the Virtual Environment

To exit the virtual environment, simply run:
```bash
deactivate
