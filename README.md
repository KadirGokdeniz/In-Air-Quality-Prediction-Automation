# CN-OBEE Dataset

The CN-OBEE dataset encompasses one year of data from a Chinese household. This dataset includes data that affect the air quality of six different rooms. Additionally, it provides access to weather information outside the house. Moreover, the power file contains data on the energy consumption of electrical appliances used within the household.

# Indoor Air Quality Predictor
The `Air_Quality_Prediction.ipynb` file utilizes an RNN named GRU to generate 44 days of prediction data using this information. These prediction data cover temperature, pressure, and relative humidity. Prediction data are stored in the `predictions.csv` file.

# SmartAir Controller
The `Smart-Air.py` file is a web application written with Streamlit. This application allows users to view prediction data and provides information on when the automation system will operate. Furthermore, users can suspend or schedule the system's future operations before they occur if desired. In automation pyramid, this can be accepted as a SCADA.
