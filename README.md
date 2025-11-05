Car Price Prediction

This is a simple machine learning web app built using Streamlit. It predicts car prices based on various input features using a trained regression model.

How It Works

1. The dataset (car data.csv) is cleaned, encoded, and scaled in carprice.py.
2. The trained model is saved as model.pkl.
3. The Streamlit app (streamlit.py) provides a user interface to input car details.
4. The model predicts the selling price of the car and displays it on the web app.

Project Structure

car_price/
│
├── carprice.py           Model training script
├── streamlit.py          Streamlit web app
├── model.pkl             Trained ML model
├── scaling.pkl           Saved scaler
├── Fuel_Type.pkl         Encoded fuel type data
├── Transmission.pkl      Encoded transmission data
├── car data (2).csv      Dataset
└── __pycache__/          Cached files

Steps to Run

1. Install Dependencies

   pip install -r requirements.txt

   (If not provided, install manually: streamlit, pandas, numpy, scikit-learn)

2. Train the Model (optional)

   python carprice.py

3. Run the Streamlit App

   streamlit run streamlit.py

   Then open your browser and go to the link shown in the terminal.

Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
