### **Image Background Removal and Transformation Tool**

Welcome to the **Image Background Removal and Transformation Tool**! This project is a Python-based application that allows you to easily remove image backgrounds and apply transformations like converting images to **8-bit** or **Black and White**. The tool is built using the `rembg` library, `Pillow`, and Jupyter widgets for a user-friendly interactive experience.

---

### **Features**

1. **Background Removal**:
   - Removes the background from uploaded images seamlessly.

2. **Image Transformations**:
   - **8-Bit Conversion**: Transforms the image into a retro 8-bit style.
   - **Black and White**: Converts the image to grayscale.

3. **Interactive UI**:
   - Powered by Jupyter widgets for easy image upload, processing, and display.

4. **Save Processed Images**:
   - Save the transformed image locally as `processed_image.png`.

---

### **File and Folder Structure**

```bash
ImageProcessor/
├── main.py                      # Main script for the tool
├── requirements.txt             # Dependencies for the project
├── README.md                    # Documentation for the project
```

---

### **Installation Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thekartikeyamishra/ImageProcessor.git
   cd ImageProcessor
   ```

2. **Set Up Virtual Environment (Optional)**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   Open a Jupyter Notebook and run the `main.py` script.

---

### **Requirements**

The project uses the following Python libraries:
- `rembg`: For background removal.
- `Pillow`: For image processing and transformations.
- `ipywidgets`: For building an interactive UI in Jupyter.
- `IPython`: To display widgets and outputs.

Install them using:
```bash
pip install rembg pillow ipywidgets IPython
```

---

### **How to Use**

1. **Open the Tool**:
   Launch the Jupyter Notebook and execute the script.

2. **Upload an Image**:
   Use the **File Upload widget** to select an image.

3. **Choose a Transformation**:
   - **Original (Background removed)**: Removes the image background.
   - **8-Bit**: Converts the image to an 8-bit style.
   - **Black and White**: Converts the image to grayscale.

4. **Process the Image**:
   Click the **Process Image** button to apply the selected transformation.

5. **View and Save**:
   - The tool displays the original and processed images.
   - The processed image is saved locally as `processed_image.png`.

---

### **Future Enhancements**

1. **Batch Processing**:
   - Support for uploading and processing multiple images simultaneously.

2. **Additional Transformations**:
   - Add filters like sepia, blur, or edge detection.

3. **Web App**:
   - Convert the tool into a web application for broader accessibility.

4. **Mobile Compatibility**:
   - Develop a mobile version for on-the-go image processing.

---

### **Contribute**

Contributions are welcome! If you have ideas for new features or enhancements:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

### **Support**

If you find this project useful, consider giving it a ⭐ on GitHub: [Image Background Removal and Transformation Tool](https://github.com/your-username/ImageProcessor).

---

Enjoy transforming your images! 🚀
