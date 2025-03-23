# Diabetic Retinopathy Dataset Exploratory Data Analysis

## Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Diabetic Retinopathy dataset, focusing on understanding the dataset structure, distribution, and image characteristics to support the development of automated detection systems for diabetic retinopathy.

## Table of Contents
- [Dataset Structure](#dataset-structure)
- [Image Distribution Analysis](#image-distribution-analysis)
- [Image Dimension Analysis](#image-dimension-analysis)
- [Key Findings](#key-findings)
- [Requirements](#requirements)
- [Usage](#usage)

## Dataset Structure
The analysis explores the hierarchical organization of the dataset:
- Total number of images
- Class distribution (severity levels)
- File organization and naming conventions
- Data quality assessment
- Missing or corrupted files identification

## Image Distribution Analysis
Detailed breakdown of the dataset distribution:
- Class-wise image count:-
- Training/Validation/Test split analysis:{'train': 73995, 'val': 9245, 'test': 9261}
- Balance/imbalance assessment
- Distribution visualization through charts and graphs

## Image Dimension Analysis
Comprehensive analysis of image dimensions:
- Resolution distribution 512x512
- Aspect ratio analysis
- Size variations:null
- Standardization requirements:null
- Storage implications:20Gigs

## Key Findings
1. **Dataset Composition**
   - Distribution of severity levels
   - Quality metrics summary
   - Identified patterns and anomalies

2. **Technical Characteristics**
   - Resolution ranges
   - Common image properties
   - Preprocessing requirements

3. **Challenges Identified**
   - Class imbalance issues
   - Quality variations
   - Standardization needs

## Requirements
```python
numpy==1.21.0
pandas==1.3.0
matplotlib==3.4.2
seaborn==0.11.1
opencv-python==4.5.3
pillow==8.3.1
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/username/diabetic-retinopathy-eda.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to the notebooks directory:
   ```bash
   cd notebooks
   ```

4. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

## License
This project is licensed under the MIT License
## Acknowledgments
- Dataset providers:Kaggle and respective Author.
- Research community:Hurer, Abdul, Deeksha.
- Contributing organizations:MIT

## Contact
For questions or feedback, please open an issue or contact [mohammedabuhurer@email.com]
