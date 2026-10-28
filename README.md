# Iris Flask MLOps

A machine learning web application that predicts the species of an Iris flower using a Flask-based interface. This project demonstrates how to integrate a machine learning model with a web application.

## 🌟 Project Overview

The Iris Flask MLOps project uses the famous Iris dataset to classify flowers into three species based on their measurements. A trained machine learning model is integrated with Flask to provide predictions through a web interface.

## 🎯 Objectives

- Build a machine learning classification model.
- Integrate the trained model with a Flask web application.
- Accept flower measurements as user input.
- Display the predicted Iris species.
- Understand the basics of deploying machine learning models through web applications.

## 🌸 Iris Flower Species

The model predicts one of the following species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🛠️ Technologies Used

- **Python** – Programming language
- **Flask** – Web application framework
- **Scikit-learn** – Machine learning
- **Pandas and NumPy** – Data processing
- **HTML and CSS** – Web interface
- **Git and GitHub** – Version control

## 📂 Project Structure

The exact file structure may vary depending on the repository.

```text
iris-flask-mlops/
├── app.py
├── model.pkl
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/iris-flask-mlops.git
```

### 2. Navigate to the Project Directory

```bash
cd iris-flask-mlops
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

If the Flask entry-point file is `app.py`, run:

```bash
python app.py
```

Open the local URL displayed in the terminal, commonly:

```text
http://127.0.0.1:5000/
```

## 🔍 How It Works

1. The user enters the measurements of an Iris flower.
2. The application receives the input through the Flask interface.
3. The trained machine learning model processes the measurements.
4. The model predicts the flower species.
5. The predicted result is displayed on the web page.

## 📊 Dataset

The Iris dataset contains measurements of Iris flowers, including:

- Sepal length
- Sepal width
- Petal length
- Petal width

These features are used to classify flowers into three species.

## 🚀 Future Improvements

- Deploy the application to a cloud platform.
- Add model evaluation metrics and visualizations.
- Implement automated model training and testing.
- Add CI/CD integration.
- Monitor model performance and prediction quality.

## 📚 Learning Outcomes

- Understanding machine learning classification.
- Integrating Scikit-learn models with Flask.
- Building interactive ML web applications.
- Managing projects with Git and GitHub.
- Exploring introductory MLOps workflows.

## 👩‍💻 Author

**Vasudha Lohar**

GitHub: [YOUR-USERNAME](https://github.com/YOUR-USERNAME)

## 📄 License

Check the original repository's license before redistributing or modifying this project. If no license is provided, do not assume that the source code is freely licensed for reuse.
