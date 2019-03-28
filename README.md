<h1>Weatherbit API</h1>

This application has been developed to receive the weather forecast for a 24 hour period in Raleigh, North Carolina, United States of America.
- The application provides a dynamically generated REST API.
- The application makes use of an external REST service to complement its functionality.
- The application uses a cloud database for accessing persistent information.
- Implemented user accounts and access management.
 
## **Installation Prerequisites**

1. Installing Python:
```
sudo apt-get install python3
```
2. Create our virtual environment with flask_venv:
```
python3 -m venv flask_venv
```
3. Activate virtual environment:
```
source flask_venv/bin/activate
```
4. Now, switch to your terminal. From your app directory (the same directory that has your requirements.txt) run the following:
```
python -m pip install -U -r requirements.txt
```
## **Running the Application**

1. Run the conversion application:
```
python app.py
```
2. Open your browser and navigate to localhost:8080
3. Enter the user name : identification1 and the password : weather 
4. Access the page and enter information.
5. City: Raleigh 
6. Enter start date (yyyy-mm-dd) and end date (yyyy-mm-dd), start date is 2019-03-15 and end date is 2019-03-16 
7. Enter the hour of the 24 hour day that you would like to see ( 1 -24 ) 
7. Click the submit button.

