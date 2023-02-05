House Price Prediction Web Application


This is a Flask-based web application that utilizes advanced machine learning algorithms to predict the prices of houses based on user-inputted features. 
The application is deployed on Apache server and hosted on Amazon Web Services (AWS) Cloud, offering a fast and reliable user experience.


Getting Started


These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites


--Python 3.x

--Flask

--Apache server

--AWS account (for hosting)

Installing

1. Clone the repository to your local machine

$ git clone https://github.com/Manusd04/House-Price-Predictor-Website.git


2. Navigate to the project directory

$ cd house-price-prediction


3. Install the required packages

$ pip install -r requirements.txt



4. Start the Flask development server

$ export FLASK_APP=app.py


$ flask run


The web application should now be running on your local machine at http://localhost:5000/.


Deployment

The application can be deployed on Apache server and hosted on AWS Cloud using the following steps:

1.Install Apache server on your local machine

2.Copy the entire project directory to the Apache server's htdocs folder

3.Set up the necessary configurations on Apache to serve the Flask application

4.Create an AWS account and set up an AWS ec2 instance to host your application

5.Deploy the application to the AWS ec2 instance bucket



Please refer to the official Flask and AWS documentation for detailed instructions on deploying Flask applications.


Built With

[Flask](https://flask.palletsprojects.com/en/2.0.x/) - A Python web framework

[Apache server](https://httpd.apache.org) - A popular open-source web server

[AWS Cloud](https://aws.amazon.com) - Amazon Web Services for hosting

Authors

[MANU S D](https://github.com/Manusd04)

License

This project is open source and does not have a license.


Contributions, bug reports, and suggestions for improvements are welcome and encouraged. Feel free to open an issue or submit a pull request with any changes or advice to improve the project.
