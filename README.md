<h1 align="center"> Bangalore House Price Predictor </h1>

<p> Simple website powered by a powerful model developed using <b>SciKit-Learn Package</b>. The website takes in basic information(parameters) like the size of the house in square feet, number of rooms and the location of the house in bangalore to predict the price of the house.</p>

<h1> Python Packages Used </h1>
  
- SciKit-Learn [Model Development Framework]
- Flask [Framework for Website Backend]
- Numpy [Model Calculations]
- Pickle [Model Dumping and Loading]
- Flake8 [Linting]

<h1> Setting Up on Local Machine </h1>

<h2> Manual Setup </h2>

1. Clone the repository using `git clone https://github.com/Namratha2301/BangaloreHousePricePredictor.git`
2. Navigate to the cloned repository using `cd BangaloreHousePricePredictor`
3. Setup Python Virtual Environment using either `python -m venv env` or `<path-to-pythonexe -m venv env`
4. Once `env` folder is created run `env\Scripts\Python.exe -m pip install --upgrade pip` to update pip version to latest
5. Now `cd server` and install the dependencies using  `pip install -r requirements.txt`
6. After the dependencies have been installed run the server using `python server.py`

The website will be visible at `http://127.0.0.1:5000`.

<h2> Setup Using Docker </h2>

1. Clone the repository using `git clone https://github.com/Namratha2301/BangaloreHousePricePredictor.git`
2. Navigate to the cloned repository using `cd BangaloreHousePricePredictor`
3. Run `docker-compose up` to launch the container and view the site at `http://127.0.0.1:5000`
4. Inorder to relaunch the container in case of any edits to the programs run the comamnd `docker-compose up --build`

