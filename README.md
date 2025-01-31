# EasyOCR_Numeric_Data_Extraction
Developed an OCR-based system to extract handwritten numeric information from scanned cadastral map images.

# OCR System for Extracting Numbers Using EasyOCR

This project implements an OCR system using EasyOCR for extracting numeric information from images.

## Setup Instructions
1. Clone or download this repository.
2. Install the required dependencies:
3. Open the Jupyter Notebook (`EasyOCR_Numeric_Data_Extraction.ipynb`) in Google Colab or locally.

## Usage
1. Place your input images in the same directory or specify their path in the notebook.
2. Run the notebook cells sequentially.
3. The extracted numeric information will be saved as CSV files.

## Output
- The processed images will be displayed with bounding boxes in the notebook.
- Extracted numeric information will be saved as a CSV file (e.g., `output.csv`).

## Dependencies
- Python 3.7+
- OpenCV
- EasyOCR
- Pandas
- NumPy
- Scikit-learn


EasyOCR_Numeric_Data_Extraction/
├── EasyOCR_Numeric_Data_Extraction.ipynb     # Main notebook for numeric data extraction using EasyOCR  
├── README.md                                 # Overview of the project, installation, and usage instructions  
├── requirements.txt                          # List of Python dependencies required to run the project  
├── Input_Files/                              # Folder containing scanned cadastral map images  
│   ├── VW_DTN01_L_00007_101000000000000000002038853600000.jpg
│   └── VW_DTN01_A_00002_101000000000000000002051033000000.front.jpg # Example input image  
├── output/                                    # Folder for storing results and outputs  
│   ├── output_ocr.csv                        # Annotated OCR output for image analysis  
│   ├── extracted_data/                       # Subfolder for CSV files containing extracted numeric data  
│   │   ├── output_img01_1.csv                # Extracted numbers from image 1 (method 1)  
│   │   ├── output_img02_1.csv                # Extracted numbers from image 2 (method 1)  
│   │   ├── output_img01_2.csv                # Extracted numbers from image 1 (method 2)  
│   │   └── output_img02_2.csv                # Extracted numbers from image 2 (method 2)  
                                 

