# Flight Fare Prediction - a Classic Time Series Project .
* Flight fare prediction is a classical problem of time series forecasting that finds trends in past observations to outline the future
* Many popular flight booking websites today, including Google Flights, showcase important insights on:
  * Current fair status: high, low or fair
  * Past fare trends, upcoming future trends and 
  * Helps decide the right time to book a flight ticket.
* In this project, we are going to build a Python Flight Fare Prediction App, that returns the fare prediction for a given set of travel details, like:  departure date, arrival date, departure city, arrival city, stoppages, and the airline carrier.

## App Functionality
![](templates/App_Functionality.gif)

## Steps to run Flight Fare App 

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://git-scm.com/downloads) Client 
* Open GIT CMD >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

      git clone https://github.com/skillcate/flight-price-prediction.git  
* Open Windows Powershell >> navigate to new working directory (cloned repo folder)
* Run Project in Flask (Using PIP + Virtualenv)
 
        pip install virtualenv                  # install virtual environment        
        virtualenv ENV                          # create virtual environment by the name ENV
        .\ENV\Scripts\activate                  # activate ENV
        pip install -r .\requirements.txt       # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done
  

                       # close virtual environment once done
        

### Important links:
* [Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

