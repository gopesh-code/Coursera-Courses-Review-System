# Coursera Courses Review System

## Overview

This project focuses on analyzing student reviews of Coursera courses. It leverages **Latent Dirichlet Allocation (LDA)** for topic modeling and **Sentiment Analysis** to gauge the overall sentiment of student feedback. This system provides insights into course quality, content coverage, and areas for improvement based on user-generated reviews.

## Features

- **LDA-based Topic Modeling**: Identifies the main themes discussed in course reviews.
- **Sentiment Analysis**: Classifies student reviews as positive, negative, or neutral using Natural Language Processing (NLP) techniques.
- **Jupyter Notebook Implementation**: The project code is provided in a Jupyter Notebook for ease of understanding and reproducibility.

## Technologies Used

- **Python**: Primary programming language.
- **Jupyter Notebook**: For code implementation.
- **NLTK**: Library for text processing and sentiment analysis.
- **Scikit-learn**: For LDA topic modeling and data analysis.
- **Pandas**: Data handling and manipulation.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gopesh-code/Coursera-Courses-Review-System.git
   cd Coursera-Courses-Review-System
   ```

2. **Set up virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # For Windows: env\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:
   Open `Team_12_Project_Code.ipynb` in Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

- **Data Input**: The notebook accepts reviews in CSV format.
- **LDA**: Apply topic modeling to the reviews to find common themes.
- **Sentiment Analysis**: Perform sentiment classification to analyze the mood of the reviews.

## File Structure

```plaintext
├── data/                   # Directory for dataset (course reviews)
├── notebooks/              # Jupyter Notebooks for analysis
├── requirements.txt        # Dependencies
├── Team_12_Project_Code.ipynb  # Main code
└── README.md               # This file
```

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
