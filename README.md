# HackNUThon

How to run the website along with model

BACKEND =>

go to backend folder=>
cd backend

in Backend folder create a python virtual environment using =>
python -m venv model

to activate the virtual environment =>
.\model\Scripts\activate 

after activating install dependencies =>
pip install flask flask-cors lightgbm pandas numpy scikit-learn optuna joblib gunicorn google-generativeai python-dotenv

to run backend server =>
flask run
(while virtual environment in python is active)


FRONTEND => 

go to frontend folder=>
cd frontend

install dependencies using npm =>
npm install

run the frontend server =>
npm run dev
