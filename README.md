# Car Dataset-data preprocessing

This repository contains a dataset of cars and their characteristics scraped from the Wandaloo website, as well as a Jupyter notebook that includes data preprocessing, visualization, and a model for predicting car prices.

## Dataset

The dataset is provided in CSV format and includes the following columns:

- `Brand`: The name of the vehicle manufacturer
- `Model`: The specific type or design of vehicle within the brand
- `Version`: The specific variation or edition of a vehicle model
- `Price`: The vehicule's cost
- `Model year`:The year in which the model was released to the market for sale
- `Hand`: The number of previous owners a vehicle has had.
- `Mileage`: how far the vehicle has traveled over its lifetime.
- `Fuel type`: The fuel that powers the engine to produce the necessary energy for the propulsion of the vehicle.
- `Transmision`: It specifies if the vehicule is manual or automatic.
- `Fiscal horsepower`: The measure of the administrative power of a vehicle used in some countries to determine the amount of tax to be paid on the vehicle.
- `Exterior color`
- `Vehicule condition`: The current physical state of the vehicle, including its overall appearance and mechanical condition. 
- `Air conditionning`: The type of the air conditionning in the vehicule.
- `Electric windows`: Refers to electric windows that can be controlled with buttons.
- `Electric seats`: Refers to electric seats.
- `On-board computer`:The computerized system in a vehicle
- `Start & Stop`: The technology of turning off the engine when the vehicle is stationary and then restarting it when the driver is ready to move again.
- `Cruise control`: The feature in a vehicle that allows the driver to set and maintain a steady speed.
- `Automatic headlights`: The feature in a vehicle that allows the headlights to turn on and off automatically based on external lighting conditions.
- `Rain sensor`: The device that is installed on a vehicle's windshield and is designed to automatically activate the windshield wipers when it detects rain or moisture.
- `Steering wheel controls`: The feature in many modern vehicles that allow the driver to control certain functions of the car without taking their hands off the steering wheel. 
- `Touchscreen display`: The type of electronic visual display
- `Electric mirrors`: The feature in a vehicule that allow the driver to adjust the side mirrors with the push of a button.
- `Automatic trunk opening`: The featurethat allows the trunk to open and close automatically.
- `Hands-free start`: The feature a vehicle that allows the driver to start the engine without physically inserting a key into the ignition.
- `1/3-2/3 folding rear seat`: is a type of rear seat configuration commonly found in vehicles that allows the rear seat to be folded down in a flexible manner.
- `Backup camera`: a safety feature in modern vehicles that helps drivers see what is behind their vehicle when backing up.
- `Bluetooth`
- `Aluminum wheels`: a popular type of wheel used in modern vehicles.
- `Leather steering wheel`: a type of steering wheel that is covered in leather
- `Daytime running lights`: a safety feature found on many modern vehicles that are designed to improve visibility and reduce the risk of accidents during the day.
- `Roof rails`: The long bars that run along the length of the car's roof.
- `Roof`: The type of the roof
- `Airbags`: Safety devices in vehicles designed to inflate rapidly in the event of a collision
- `ABS`: Anti-lock Braking System
- `ESP`: Electronic Stability Program. It is a safety feature in vehicles designed to help drivers maintain control of their car during sudden maneuvers
- `Traction control`: a safety feature in vehicles designed to prevent the wheels from spinning during acceleration on slippery or uneven surfaces
- `Architecture`: The design and layout of the engine's components, including its cylinders, valves, and pistons. 
- `Engine displacement`: The measure of the total volume of all the cylinders in an internal combustion engine. 
- `City fuel consumption`: the amount of fuel that a vehicle uses while driving in city or urban environments with frequent starts and stops
- `Highway fuel consumption`: The amount of fuel that a vehicle uses while driving at high speeds on highways or motorways
- `Maximum speed`: maximun speed of the vehicule
- `Fuel tank volume`: the amount of fuel that a vehicle's fuel tank can hold

The data was scraped from the Wandaloo website using `Selenium`. The dataset includes information on over 3,000 cars and is intended for use in machine learning and data analysis projects.

## Jupyter Notebook

The Jupyter notebook included in this repository provides an example of how to preprocess, visualize, and model the car dataset. The notebook includes the following sections:

- Data preprocessing
- Data visualisation
- Feature Engineering
- Model Building and Evaluation

The notebook uses Python and several popular libraries, including NumPy, Pandas, Matplotlib, Seaborn, and Scikit-Learn.

## Getting Started

To use the dataset and Jupyter notebook in your own projects, you can clone this repository using the following command:
<br>
`git clone https://github.com/JamilaAferhane/Cars-dataset-cleaning-prediction.git`

Once you have cloned the repository, you can open the Jupyter notebook using a tool like JupyterLab or Jupyter Notebook. From there, you can modify the notebook to fit your needs or use it as a starting point for your own analysis.
