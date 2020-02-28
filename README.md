# PostgreSQL_Heroku_Tutorial
Create and connect to a Heroku PostgreSQL server by using Python in a Jupyter Notebook!

Authors: Daniel Kim & Dae Han

**To examine a real-life project application of this notebook, click here on Dae's [capstone](https://github.com/dae-han/nyc_homeless_pop_prediction/blob/master/production/1_Data_Wrangling%2BDatabase_Construction.ipynb). He built a time series model to forecast the total number of individuals sheltered by the NYC Department of Homeless Services (DHS).**

**First, go to heroku and sign up for a free account -  https://www.heroku.com/postgres**

**Click "Create new app"**

<img src="./images/01_create_app.jpeg" width="800" height = "900">

**Choose a descriptive and unique App name then click "create app"**
<img src="./images/02_app_name.jpeg" width="800" height = "900">

**Click on this [heroku add on link](https://elements.heroku.com/addons/heroku-postgresql) and click "Install Heroku Postgres"**
<img src="./images/03_install.jpeg" width="800" height = "900">

**Link the postgres add on to the app you just named.**
<img src="./images/04_postgres.jpeg" width="800" height = "900">
<img src="./images/05_add_provision.jpeg" width="800" height = "900">

**Click on "Heroku Postgres" and go to the settings and click on the database credentials.**
<img src="./images/06_creds.jpeg" width="800" height = "900">


**<font color="red">Note: Credentials are not permanent! There are other ways to obtain credentials, but this is just a simple example</font>**


Store the URI in a json file named `creds.json`.

The format in `creds.json` should be the following: ```{"uri" : "your-uri-credentials"}```. Take notice of the double quotations!

**<font color="red">DO NOT UPLOAD YOUR JSON FILE ONTO GITHUB! INCLUDE THE `creds.json` FILE IN THE GITIGNORE TEXT</font>**

