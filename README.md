# 🌍 Estimation in Earthquake Early Warning

A **Django-based web application for Earthquake Early Warning and Prediction** that uses earthquake datasets and machine-learning techniques to estimate earthquake-related warning conditions. The system provides separate interfaces for users and service providers, along with prediction, trained dataset management, results visualization, and feedback features.

## 🚀 Features

* 🌎 **Earthquake Early Warning Prediction**
* 🤖 **Machine Learning Model Training**
* 📊 **Earthquake Prediction Results**
* 📁 **Dataset Management**
* 📈 **Prediction and Result Analysis**
* 👤 **User Registration and Login**
* 🏢 **Service Provider Login**
* ⭐ **User Ratings and Reviews**
* 👍 **Likes and Dislikes Analysis**
* 📉 **Charts and Data Visualization**
* 🗄️ **Database Integration**

## 🛠️ Technologies Used

* **Python**
* **Django**
* **HTML5**
* **CSS3**
* **JavaScript**
* **MySQL**
* **Machine Learning**
* **CSV Dataset**

## 📂 Project Structure

```text
Estimation_in_Earthquake_Early_Warning/
│
├── Database/
│   └── estimation_in_earthquake_earlywarning.sql
│
├── Datastructure.txt
│
└── estimation_in_earthquake_earlywarning/
    ├── manage.py
    ├── Earthquake_Warning_Datasets.csv
    ├── Results.csv
    │
    ├── estimation_in_earthquake_earlywarning/
    │   ├── settings.py
    │   ├── urls.py
    │   ├── asgi.py
    │   └── wsgi.py
    │
    ├── Remote_User/
    │   ├── models.py
    │   ├── views.py
    │   └── forms.py
    │
    ├── Service_Provider/
    │   ├── models.py
    │   └── views.py
    │
    └── Template/
        └── htmls/
            ├── RUser/
            └── SProvider/
```

## 🎯 Project Objective

The primary objective of this project is to develop a web-based system that can analyze earthquake-related data and provide **early warning/prediction results** using machine-learning techniques. The platform also enables service providers to manage datasets, train models, review predictions, and analyze user feedback.

## 👥 User Modules

### Remote User

Users can:

* Register and log in
* Provide earthquake-related information
* View earthquake early-warning predictions
* View their profile
* Rate and review the system
* Interact with prediction-related information

### Service Provider

Service providers can:

* Log in to the system
* Manage trained datasets
* Train the prediction model
* View earthquake prediction results
* Analyze prediction statistics
* View likes/dislikes and user feedback
* Generate charts and reports

## 📊 Dataset

The project includes an earthquake dataset:

```text
Earthquake_Warning_Datasets.csv
```

The dataset is used as input for the machine-learning and prediction workflow.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Estimation_in_Earthquake_Early_Warning.git
cd Estimation_in_Earthquake_Early_Warning
```

Install the required Python packages:

```bash
pip install django
```

Configure the database using the SQL file provided in the `Database` folder.

Run Django migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

Open the application in your browser at the local Django server address.

## 🔮 Future Enhancements

* Real-time earthquake sensor integration
* Live seismic data collection
* Real-time earthquake alerts
* Improved machine-learning models
* Interactive earthquake maps
* SMS and mobile notifications
* Integration with public seismic APIs
* Improved prediction accuracy and evaluation

## ⚠️ Disclaimer

This project is intended for **educational and research purposes**. Earthquake prediction is a complex scientific problem, and this application should not be considered a replacement for official earthquake monitoring or emergency-warning systems.
