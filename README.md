# K-Means Clustering

This project provides a web-based interface for performing K-Means clustering on uploaded images. Users can upload an image, specify the number of clusters (k), and receive a segmented version of the image based on the K-Means algorithm.

## Features

- Upload an image through the web interface.
- Specify the number of clusters for the K-Means algorithm.
- View the original image and its clustered version side-by-side.
- Responsive and clean UI with styled CSS.

---

## Installation

### Prerequisites

1. Python installed.
2. A virtual environment (recommended).
3. Flask and required Python libraries.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/mzums/k-means
   cd <repository-folder>
   ```

2. Create a virtual environment:
   ```bash
   python -m venv kmeans
   source kmeans/bin/activate   # Linux/Mac
   kmeans\Scripts\activate      # Windows
   ```

3. Install dependencies:


4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

---

## Folder Structure

```
.
├── app.py               # Main Flask application
├── static/              # Static assets (e.g., CSS, images)
│   ├── styles.css       # CSS for the web interface
├── templates/           # HTML templates
│   ├── index.html       # Main page
├── uploads/             # Directory for uploaded images
└── outputs/             # Directory for clustered images
```

---

## How It Works

1. **Image Upload**: Users upload an image and specify the number of clusters (`k`).
2. **Processing**:
   - The backend runs the K-Means algorithm on the uploaded image using Python.
   - The segmented image is saved to the `outputs/` directory.
3. **Results**: The original and segmented images are displayed side-by-side.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and create a pull request.

---

## Future Improvements

- Add support for more image formats.
- Implement more algorithms with k-means.
- Enhance UI/UX further. 
