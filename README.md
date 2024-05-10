

# Customer Churn Analysis Project

This project aims to analyze customer churn in a telecommunications company using machine learning techniques. It includes exploratory data analysis (EDA), model training, interpretation using SHAP values, and a Streamlit web application for interactive visualization and churn probability prediction.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn, the phenomenon of customers ceasing to do business with a company, is a critical metric for businesses, especially in subscription-based industries like telecommunications. This project employs machine learning models to predict customer churn based on historical customer data and provides insights into the factors influencing churn decisions.

## Project Structure

The project is structured as follows:

- **data_files/**: Contains the datasets used for training and testing the model.
- **docker/**: Docker configuration files for containerization.
- **models/**: Trained machine learning models saved as files.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and model development.
- **src/**: Source code files including Streamlit web application, model training scripts, and FastAPI integration.
- **tests/**: Unit tests for the source code.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/customer-churn-analysis.git
```

2. Install dependencies:

```bash
cd customer-churn-analysis
pip install -r requirements.txt
```

## Usage

### Running the Streamlit Web Application

```bash
streamlit run src/app.py
```

Visit the URL provided in the terminal to access the web application.

### Training the Model

To train the model, run:

```bash
python src/train_model.py
```

### Predicting Churn Probability

To predict churn probability for a new customer, run:

```bash
python src/predict.py
```

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests for any improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

