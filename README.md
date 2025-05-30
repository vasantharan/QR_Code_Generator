# QR Code Generation App

A simple web application to generate QR codes from text or URLs using Streamlit. 
This app allows you to input any text or link, generate its QR code instantly, 
preview the result, and download it as a PNG file.

---

## Features

- Generate QR codes from text or URLs
- View the generated QR code directly in the app
- Download the QR code as a PNG image
- Lightweight and easy-to-use interface

---

## Requirements

- Python 3.10 or higher
- streamlit
- qrcode
- pillow

All dependencies are listed in requirements.txt

---

## Installation

1. Clone or download this repository:
   ```
   git clone https://github.com/vasantharan/QR_Code_Generator.git
   cd QR_Code_Generator
   ```
   
2. Create a virtual environment
   ```
   python -m venv env
   ```
   
3. Activate the virtual environment:
   - On Windows: ``` env\Scripts\activate ```
   - On macOS/Linux: ``` source env/bin/activate ```
   
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
   
5. Run the application:
   ```
   streamlit run main.py
   ```

---

## File Structure

- main.py              --> Main application script using Streamlit  
- requirements.txt     --> Required Python libraries  
- LICENSE              --> Apache License 2.0  
- README.txt           --> This file

---

 ## Usage

1. Open the app in your browser.
2. Enter any text or URL in the input field.
3. Click on "Generate" to view the QR code.
4. Click "Download" to save the QR code image.

---

## License

This project is licensed under the Apache License 2.0.
See the LICENSE file for full license text.

---

## Author

- Developed by **Vasantharan K** 
- GitHub: https://github.com/vasantharan  
- Portfolio: https://www.vasantharan.in
