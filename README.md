# image-upscaler
---

Transform your low-resolution images into stunning high-quality masterpieces (4x upscaling) with ease using our Flask web application. Powered by AI image upscaling technology, it effortlessly enhances the details and sharpness of your images. Elevate your visual content and impress your audience with every click. 

![ImageUpscaler](image.png "Elevate your low-res images effortlessly with our Flask web app powered by AI image upscaling.")

## Dependencies
---

* Git
* Pytnon 3.12

## Run
---

### 1. Clone repository

```bash
git clone https://github.com/thereisnouser/image-upscaler.git
cd image-upscaler
```

### 2. Create a Virtual Environment

```bash
# Windows
python -m venv .venv
.\.venv\Scripts\activate

# Linux / macOS
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

### 5. Usage

1. Open your browser and go to http://127.0.0.1:5000/
2. Upload an image using the form
3. Get the enhanced (×4 upscaled) version of your image