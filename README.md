# ⚡ nexa-mfrr-nordic-eam - Build Nordic bids with ease

[![Download](https://img.shields.io/badge/Download-Open%20GitHub%20Page-blue?style=for-the-badge)](https://github.com/Tobiahhalfwitted492/nexa-mfrr-nordic-eam)

## 🧭 What this is

nexa-mfrr-nordic-eam is a Python library for building, checking, and saving mFRR energy activation market bids. It helps with CIM XML document creation for BSPs that create their own bid files for the Nordic TSOs.

This project is for users who work with energy market bid files and need a clear way to prepare them for transfer or validation. It supports workflows linked to Statnett, Fingrid, Energinet, and Svenska kraftnät.

## 📦 What you can do with it

- Build mFRR EAM bid data
- Validate bid content before use
- Create CIM XML documents
- Prepare files for Nordic TSO workflows
- Work with market data in a Python-based setup
- Support internal bid generation for BSP teams

## 💻 What you need

- A Windows computer
- Internet access
- A web browser
- Python 3.10 or newer
- Permission to install software
- A place to save the files you download

## 🚀 Download and run

Open the GitHub page here:

[https://github.com/Tobiahhalfwitted492/nexa-mfrr-nordic-eam](https://github.com/Tobiahhalfwitted492/nexa-mfrr-nordic-eam)

If the page includes a release file, download that file and run it on your Windows PC.

If the page gives you source files instead of an app file, download the project files and follow the steps below to use them on Windows.

### 1. Download the project

1. Open the GitHub page in your browser.
2. Look for a green `Code` button.
3. Click it.
4. Choose `Download ZIP`.
5. Save the ZIP file to a folder you can find later, such as `Downloads`.

### 2. Unpack the files

1. Find the ZIP file you downloaded.
2. Right-click it.
3. Choose `Extract All`.
4. Pick a folder for the extracted files.
5. Open the new folder after extraction.

### 3. Install Python

1. Go to [python.org](https://www.python.org/downloads/windows/).
2. Download the latest Python installer for Windows.
3. Run the installer.
4. Check `Add Python to PATH`.
5. Finish the install.

### 4. Open Command Prompt

1. Press `Windows + R`.
2. Type `cmd`.
3. Press `Enter`.
4. A black window will open.

### 5. Go to the project folder

Type the folder path where you extracted the project, then press `Enter`.

Example:

```text
cd C:\Users\YourName\Downloads\nexa-mfrr-nordic-eam-main
```

### 6. Install the Python package tools

Type this command and press `Enter`:

```text
pip install -U pip
```

If the project includes a requirements file, install the needed packages with:

```text
pip install -r requirements.txt
```

### 7. Run the project

If the project includes a script file, run it with Python.

Example:

```text
python main.py
```

If the project uses a different entry file, open the project folder and look for a file such as:

- `app.py`
- `main.py`
- `run.py`

Then run the one that starts the app.

## 🪟 Windows setup tips

- Keep the project in a simple folder path
- Avoid folders with special characters
- Use a folder like `C:\nexa-mfrr-nordic-eam`
- Close and reopen Command Prompt if Python does not work right away
- If Windows blocks the file, right-click it and choose `Run as administrator` only when needed

## 🧩 How the library fits into your work

This library is built for a market bid flow where data must be prepared in a strict format. It helps you:

- Create bid messages in a known structure
- Check data before sending it
- Write XML that fits CIM-based exchange needs
- Reduce manual file work
- Keep bid generation consistent across runs

## 🗂️ Example project flow

A common flow can look like this:

1. Gather market bid data
2. Load the data into the library
3. Validate the bid content
4. Generate the CIM XML file
5. Save the file to disk
6. Send or use the file in your market process

## 📘 Basic use

If you use Python code with this library, the work usually looks like this:

- Import the package
- Create a bid object
- Add market values
- Validate the bid
- Export the result as XML

Example shape of use:

```python
from nexa_mfrr_nordic_eam import Bid

bid = Bid()
bid.validate()
xml_data = bid.to_xml()
```

The exact class names and method names may differ based on your version, but the process is usually the same.

## 🔍 File types you may see

You may find these files in the project:

- `README.md` — project guide
- `requirements.txt` — Python package list
- `.py` files — Python source code
- `.xml` files — example output or templates
- `LICENSE` — usage terms

## 🛠️ Common problems

### Python is not recognized

Check that Python is installed and that `Add Python to PATH` was selected during install. Then close Command Prompt and open it again.

### pip does not work

Try this command:

```text
python -m pip install -U pip
```

### The script does not start

Check that you are in the correct folder. Make sure you are running the file that starts the project, such as `main.py`.

### XML output is not what you expect

Check the input values first. Market files often need strict field names, formats, and time values.

## 🔐 Data and validation

This project focuses on structured market data. That means it can help you catch issues before files are used in a larger workflow. Good validation can reduce bad inputs, wrong formats, and missed fields.

## 🧠 Who this is for

- BSP teams
- Market ops staff
- Energy traders
- Developers working with Nordic balancing data
- Users who need CIM XML output for mFRR EAM use

## 📎 Topics

balancing-market, bsp, cim-xml, electricity-market, energinet, energy-trading, entso-e, fingrid, mari, mfrr, mfrr-eam, nordic-balancing-model, nordpool, python, statnett, svenska-kraftnat

## 📁 Project source

[Visit the GitHub repository](https://github.com/Tobiahhalfwitted492/nexa-mfrr-nordic-eam)

## 🧭 What to do next

1. Open the repository page
2. Download the files
3. Install Python on Windows
4. Run the project from the command line
5. Use the library to build and validate your mFRR EAM files