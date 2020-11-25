IPL Score Prediction</h1>
This is used to predict the IPL Score of the team by taking inputs.

<h1>Prerequisites</h1>
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

<h1>Project Structure</h1>
This project has four major parts :

app.py - This contains Flask APIs that receives Batting team, Bowling team and other details through GUI or API calls, computes the precited value based on our model and returns it.\n
templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
Ensure that you are in the project home directory. Create the machine learning model by running below command -
python app.py
This would create a serialized version of our model into a file iplscores.pkl

Run app.py using below command to start Flask API
python app.py
By default, flask will run on port 5000.

Navigate to URL http://localhost:5000
You should be able to view the homepage as below : alt text

Enter valid numerical values in all 3 input boxes and hit Predict.

If everything goes well, you should be able to see the predcited salary vaule on the HTML page! alt text

You can also send direct POST requests to FLask API using Python's inbuilt request module Run the beow command to send the request with some pre-popuated values -
python request.py
