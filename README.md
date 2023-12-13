## FrontEnd

run npm install : to download the dependencies

In the project directory, you can run:

### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Backend

run npm install : to download the dependencies

##create database with the name `repairmate` before starting the backend application

##Run the dump.sql file provided with the project to get the predefined data
##cd to folder which contains dump.sql file and run the below Command

mysql -u root -p repairmate < dump.sql


## Signup with new user to start using the application

## We are using JWT token hence user must be created from the application interface

`nodemon index.js`

Runs the app in the development mode.
http://localhost:9000

##Both MySQL and Mongo Connection included under /db directory in backend folder

##make sure to install the necessary libraries




## Commands need to Run to import all the required packages:

python -m pip install faiss-cpu
python -m pip install openai
python -m pip install langchain
python -m pip install python-dotenv
python -m pip install tiktoken
python -m pip install numpy
pip install googlemaps
pip install geopy

## database

create database repairmate;

mysql -u root -p repairmate < dump.sql

## OpenAI API New Key (Backup-only)

"----------------- USE YOUR KEY HERE ------------------"
If the given API key in the code provided, in the file named "getRecommendedRepairmates.py" under backend/PythonScript then use the above new API key.
os.environ["OPENAI_API_KEY"] = "" (add openAPI key here, sometime provided openAPI key might be invalidated in that case please create the new one)
