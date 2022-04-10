# demo-flask-app-builder
Simple and rapid application development framework, built on top of Flask. It includes detailed security, auto CRUD generation for your models and google charts.

### Installation 
pip install Flask-AppBuilder

### To download app skeleton from Github (Will ask for App name and DB type(SQLAlchemy))
flask fab create-app

## Following steps need to be run from the app folder
### To create admin user 
flask fab create-admin

### To Run the app using 
set FLASK_APP=app
set FLASK_DEBUG=1
flask run

### URL 
http://127.0.0.1:5000/

## Pictures

#### Login Page
![image](https://user-images.githubusercontent.com/39857587/162568400-716df414-3f8c-42ab-9a1f-bd13761c9f2b.png)

#### Security Page
![image](https://user-images.githubusercontent.com/39857587/162569622-e9a03315-01e5-4ea2-91ce-720009fc626a.png)

#### CRUD
![image](https://user-images.githubusercontent.com/39857587/162569657-6780859e-b32f-4110-ac90-546efe8f8c83.png)

#### Charts
Bar chart
![image](https://user-images.githubusercontent.com/39857587/162569680-525c7e24-7433-4431-b06f-c181e5d68ecc.png)

Line chart
![image](https://user-images.githubusercontent.com/39857587/162569711-7970f9dc-04f0-4d14-aac6-2aedb3216853.png)

Pie chart
![image](https://user-images.githubusercontent.com/39857587/162569729-6ba0e1b5-ee81-4957-a087-afce870fd040.png)

