# 🖼️ Web-Based Image Steganography

This project implements an image steganography web application to hide and retrieve secret messages from images. The app uses **Flask** as the web framework and supports LSB-based encoding with optional AES and DCT-based encryption methods.

## 📁 Folder Structure

```
image-steganography/
├── app.py
├── model.py
├── forms.py
├── requirements.txt
├── PNG Images/
├── Test Images/
├── static/
├── templates/
├── lsb/
├── lsb_aes/
├── dct_aes/
├── data_freq.pkl
├── e-dummy.txt
├── testimg.jpg
└── NOTEBOOK.ipynb
```

## 🚀 Project Features

- Encode messages into images using:
  - LSB (Least Significant Bit)
  - DCT + AES
- Decode messages from stego images
- Display encrypted/decrypted image previews
- Web UI using Flask
- Jupyter Notebook implementation for logic exploration

---

## 🛠️ Setup Instructions (Using Flask)

### 1. Clone the repository

```bash
git clone https://github.com/patnamsanjana15/image-steganography.git
cd image-steganography
```

### 2. Create a virtual environment (optional but recommended)

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies

You can either install individually or use the requirements file:

```bash
pip install flask==2.2.2
pip install werkzeug==2.2.2
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python app.py
```

Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🧪 Optional: Run the Notebook

You can explore or test the code inside the notebook:

```bash
jupyter notebook NOTEBOOK.ipynb
```

---

## 🧑‍💻 Author

