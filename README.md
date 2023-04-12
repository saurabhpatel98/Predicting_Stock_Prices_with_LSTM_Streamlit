
"# Predicting_Stock_Prices_with_LSTM_Streamlit" 

This code is for a web app that predicts stock prices using machine learning. It uses the Streamlit library for building the user interface, Pandas for data manipulation, yfinance for fetching stock data, NumPy for numerical operations, Matplotlib and Plotly for data visualization, and Keras for building a Long Short-Term Memory (LSTM) model for predicting stock prices. The app allows the user to select a stock from a list of companies and also provides an option to enter a custom stock symbol. After selecting a stock, the app downloads the stock data for the last 10 years, preprocesses the data, and trains an LSTM model on the data to make future price predictions. Finally, the predicted prices are visualized using Plotly. The app also calculates the root mean squared error (RMSE) between the predicted and actual prices. This code can be used as a starting point for building a web app for stock price prediction.

This is a Python-based tool that allows users to compare multiple stocks and visualize their performance through interactive charts. Some of the key features of this tool include:

1. Compare multiple stocks: Users can compare the performance of up to five stocks at once, allowing them to quickly spot trends and make informed investment decisions.
2. Improved chart: The tool includes an interactive chart that displays detailed stock information such as price, volume, and moving averages. Users can zoom in and out of the chart to better analyze the data.
3. Easy to use: The tool has a simple command-line interface that allows users to quickly enter the stocks they want to compare and view the results.

With this tool, users can easily compare the performance of different stocks and make informed investment decisions based on the data.

![compare_stocks](https://user-images.githubusercontent.com/26132974/231573779-7a2807f7-eb88-434d-8056-1f1852fc674f.png)
![home_page](https://user-images.githubusercontent.com/26132974/231573780-f7915c8d-2b00-44f6-b7e1-408275f13e80.png)
![Two_or_more_stock_compare](https://user-images.githubusercontent.com/26132974/231573781-3d983621-543f-4f9a-8057-31095aadeea4.png)


* Create a virtual environment
  * install virtual environment
 
        pip install virtualenv
        
  * create virtual environment by the name ENV
        
        virtualenv ENV
        
  * activate ENV

        .\ENV\Scripts\activate
        
* Install project dependencies

      pip install -r .\requirements.txt
      
* Run the project

      python app.py
      
* Look for the local host address on Powershell screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
* Try out your Amazon Alexa test reviews and look for results
* To close >> Go back to Powershell & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate


### Steps to run on Mac

* Prerequisites: [Python 3.9](https://www.python.org/downloads/)
* Open Terminal >> navigate to working directory >> Clone this Github Repo

      git clone https://github.com/saurabhpatel98/Predicting_Stock_Prices_with_LSTM_Streamlit.git  
* Navigate to new working directory (cloned repo folder)
* Create a virtual environment
  * install virtual environment

        pip install virtualenv
        
  * create virtual environment by the name ENV
  
        virtualenv ENV  
  * activate ENV
        
        source ENV/bin/activate
* Install project dependencies

      pip install -r requirements.txt  
* Run the project

      python app.py
      
* Look for the local host address on Terminal screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
* Try out your Amazon Alexa test reviews and look for results
* To close >> Go back to Terminal & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate
      

      

