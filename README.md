DIP: Smart Image Enhancement System
Author: Noor-ul-ain

Registration ID: 235135

Instructor: Mr. Ghulam Ali

🚀 Project Overview
This repository contains a professional, single-window GUI application developed for the Digital Image Processing (DIP) course. The system is built using Python, leveraging OpenCV for high-speed image manipulation and Matplotlib for statistical data visualization.

🛠️ Key Features
The application is divided into six logical modules corresponding to lab requirements:

Acquisition (Lab 01): Image loading, metadata extraction (resolution/dtype), and pixel matrix inspection.

Sampling & Quantization (Lab 02): Integrated analysis of spatial resolution reduction and bit-depth degradation.

Geometric Transforms (Lab 03): Real-time rotation and horizontal shearing controls.

Intensity Transforms (Lab 04): Implementation of Negative, Logarithmic, and Power-Law (Gamma) transformations.

Histogram Analysis (Lab 05): Side-by-side comparison of original and equalized histograms.

Smart Enhancement (Lab 06): An automated pipeline combining Gamma Correction and Histogram Equalization for optimal visual output.

📂 Project Structure
Following the required organizational standards:

Plaintext
DIP-Image-Enhancement-System/
│
├── code/
│   └── main.py          # The full Integrated Suite source code
│
├── images/
│   ├── input/           # Test images used for processing
│   └── output/          # Enhanced results saved from the app
│
├── results/             # Screenshots of the app in action
│
├── README.md            # Project documentation (this file)
└── report.pdf           # Final technical lab report
⚙️ Installation & Usage
Prerequisites
Ensure you have Python installed. You will need the following libraries:

Bash
pip install opencv-python numpy customtkinter pillow matplotlib
Running the App
Navigate to the root directory and run:

Bash
python code/main.py
📊 Observations
Aliasing: Observed jagged edges during 0.25x scale sampling analysis.

False Contouring: Noted distinct intensity banding when reducing quantization to 2-bit.

Contrast Enhancement: Histogram Equalization effectively redistributed pixel intensities to improve visibility in low-contrast images.
