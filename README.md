🌾 Crop Yield Prediction

This project aims to predict crop yield (in tonnes) using machine learning techniques. By analyzing key agricultural and environmental factors such as rainfall, temperature, pesticide usage, cultivated area, and crop type, the model can estimate the expected output of a crop.

The objective is to support farmers, researchers, and policymakers in making informed decisions related to crop selection, resource allocation, and agricultural planning. Accurate yield predictions can help reduce losses, optimize input usage, and improve overall food production efficiency.

The project involves data preprocessing, model training, evaluation, and deployment using a saved machine learning model and preprocessor.


🧾 Dataset

The dataset includes features such as:

Year – Year of cultivation

Average Rainfall – in mm per year

Pesticide Usage – in tonnes

Average Temperature – in degrees Celsius

Area – Region or state where crops are grown

Item – Type of crop (e.g., Wheat, Rice)

🎯 Target Variable

Yield – Crop production (numeric value representing total output)

📊 Model Used

Decision Tree Regressor

This model is trained on the input features to learn the relationship with crop yield. It's chosen for its simplicity and ability to handle both numerical and categorical data.

🔍 Evaluation Metrics

R² Score

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

🚀 How to Use

Run the Jupyter Notebook to:

Preprocess the data

Train the model

Save the trained model and preprocessor

Use the Python script to:

Load the saved model and preprocessor

Input new data values

Get the predicted crop yield

🧪 Example Inputs

Year: 2020

Rainfall: 800 mm

Pesticides: 2.3 tonnes

Temperature: 23.5 °C

Area: Karnataka

Crop Item: Rice

📁 Files

predicting_crop_yields_checkpoints.ipynb – Jupyter notebook with training and saving logic

app.py – Script to load the model and make predictions

dtr.pkl – Trained Decision Tree model

preprocessor.pkl – Preprocessing pipeline

README.md – Project overview and instructions

✅ Requirements

Python 3.x

NumPy

Scikit-learn

Flask (for interactive use, optional)

You can install them using:

bash
Copy
Edit
pip install numpy scikit-learn flask

📄 License

This project is licensed under the MIT License.
