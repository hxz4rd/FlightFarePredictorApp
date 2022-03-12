# Flight-Fare-Prediction-Web-App  
  
Link for the Web-App:-  https://mlflightfare-prediction.herokuapp.com/  

### Project Structure
This project has four major parts :
1. model.py - This contains code fot our Machine Learning model to predict flight fare absed on trainign data in 'Data_Train.xlsx' file.
2. app.py - This contains Flask APIs that receives flight details through GUI or API calls, computes the precited value based on our model and returns it.
3. templates - This folder contains the HTML template to allow user to enter flight detail and displays the predicted flight fare.
4. static - This folder contains the .css file for the html file index.html to use and render a good looking web-app.

### Guide to run the project locally
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://127.0.0.1:8000/ (This local server will be assigned after you run the unicorn command)





