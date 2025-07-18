# Food Waste Prediction Project

## Project Overview

The goal of this project is to predict food waste in an organization or supply chain by leveraging machine learning techniques like **Neural Networks** and **Linear Regression**. The project involves analyzing historical data related to food consumption and waste patterns to develop predictive models. The output of these models can help organizations reduce waste by making more accurate predictions on food usage.

## Tech Stack

- **Frontend**: React with TypeScript (TSX) and Vite
- **Backend**: Django
- **Machine Learning Models**:
  - **Neural Networks** for complex, nonlinear prediction tasks
  - **Linear Regression** for simple and interpretable prediction tasks
- **Visualization and Reporting**: Power BI for real-time data updates and dashboard reporting
- **Data Storage**: Data is stored in the backend and updated in real time for live tracking of food waste.

## Workflow

### Data Collection
The data used for predicting food waste includes historical consumption and waste data, possibly including:
- Food items consumed
- Food items wasted
- Time of day
- Environmental factors (weather, holidays, etc.)
- Supply chain variables

### Machine Learning Models
We use a combination of **Neural Networks** and **Linear Regression** to predict food waste:
1. **Neural Network**: Used to model complex relationships in the data and provide more accurate predictions.
2. **Linear Regression**: A simpler model for understanding the linear relationships between various factors and food waste.

### Backend Development (Django)
- Django serves as the backend for storing and processing data.
- It processes incoming data, applies machine learning models, and stores the predictions.
- The backend exposes APIs to send the data to the frontend in real-time.

### Frontend Development (React with TypeScript and Vite)
- The frontend is built using **React** with **TypeScript (TSX)**, providing a modern and maintainable user interface.
- **Vite** is used to quickly bundle and serve the frontend application.
- The user interface displays key metrics, predictions, and other insights regarding food waste.

### Data Visualization (Power BI)
- **Power BI** is used for visualizing real-time data updates.
- Dashboards display food waste trends, predictive analytics, and various insights.
- The data updates in real-time as new data is processed and predictions are made.

### Real-time Updates
The dashboard reflects the real-time food waste prediction by pulling data directly from the backend and visualizing it with Power BI, allowing organizations to track and respond to food waste effectively.

## How It Works

1. **Data Entry**: Food consumption and waste data are entered or collected from different sources.
2. **Model Training**: The neural network and linear regression models are trained on historical data.
3. **Prediction**: The trained models predict the amount of food waste that is likely to occur in the future.
4. **Real-Time Updates**: The backend processes these predictions and sends real-time data to the frontend.
5. **Visualization**: The frontend, powered by React and integrated with Power BI, visualizes the predictions and updates the dashboard with live data.

## Features

- **Prediction**: Predict the amount of food waste based on historical and real-time data.
- **Visualization**: Interactive dashboards in Power BI that display trends and insights on food waste.
- **Real-Time Updates**: Live tracking of food waste predictions through the frontend, updated dynamically.
- **Machine Learning Models**: Uses advanced ML models (Neural Networks and Linear Regression) to provide accurate waste predictions.

## Installation and Setup

### Backend (Django)
1. Clone the backend repository.
   ```bash
   git clone https://github.com/your-repo/food-waste-prediction-backend.git
   cd food-waste-prediction-backend
2. Set up a virtual environment and install dependencies.

python3 -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
Run migrations.

python manage.py migrate

Start the backend server.

    python manage.py runserver

Frontend (React with TypeScript and Vite)

    Clone the frontend repository.

git clone https://github.com/your-repo/food-waste-prediction-frontend.git
cd food-waste-prediction-frontend

Install dependencies.

npm install

Start the development server.

    npm run dev

Power BI Integration

    Set up Power BI to connect to the backend data source.

    Use Power BI's live data capabilities to connect to the backend API for real-time updates.

Future Improvements

    Enhanced Machine Learning Models: Integrate more advanced models like Random Forests, Gradient Boosting, etc.

    Automated Data Collection: Implement IoT devices to automatically collect real-time consumption and waste data.

    Mobile App: Create a mobile app to access the dashboard and track food waste on-the-go.

Contributing

We welcome contributions to this project! Feel free to fork the repository, submit pull requests, and open issues for discussion.
