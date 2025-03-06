# Criminal Detection System

This is a Python-based **Criminal Detection System** that allows users to store, update, and check criminal records using face recognition with DeepFace. The system also provides data visualization features for analysis.

## Features

1. **Store a New Record**: Add a criminal record with face embeddings.
2. **Update a Record**: Mark a suspect as guilty or not guilty.
3. **Check Criminal Face**: Compare an input image with stored criminal face embeddings.
4. **Generate Graphs**: Visualize gender distribution, crime statistics by state, and age distribution.
5. **Exit**: Quit the program.

## Installation

### Prerequisites
Ensure you have Python installed (Python 3.8+ recommended). Install the required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn deepface
```

### Clone the Repository
```bash
git clone https://github.com/your-username/criminal-detection-system.git
cd criminal-detection-system
```

## Usage
Run the script using:
```bash
python criminal_detection.py
```
Follow the on-screen menu options to interact with the system.

## CSV Files
- `data.csv`: Stores all records before classification.
- `guilty.csv`: Stores records of convicted criminals.
- `notguilty.csv`: Stores records of acquitted individuals.

## Face Recognition
This system uses **DeepFace** with the **Facenet512** model to extract face embeddings and compare them using cosine similarity.

## Visualization
The system provides:
- **Pie Chart**: Gender distribution of criminals.
- **Bar Graph**: Crimes categorized by state.
- **Histogram**: Age distribution of criminals.

## License
This project is licensed under the MIT License.

## Author
Developed by **Abin**.

