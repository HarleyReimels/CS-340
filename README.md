# CS-340

## Grazioso Salvare Rescue Animal Dashboard
### Project Overview

This project involves the development of a client/server application for Grazioso Salvare, an international rescue-animal training company. The application interfaces with a MongoDB database and provides a user-friendly web dashboard for interacting with the data. The dashboard allows users to filter, view, and visualize data related to dogs identified as candidates for search-and-rescue training.



### Functionality

The interactive dashboard offers the following features:

Unfiltered Data View: Displays all animal data from the Austin Animal Center Outcomes dataset.

Water Rescue Filter: Displays dogs that meet the criteria for water rescue training.

Wilderness/Mountain Rescue Filter: Displays dogs that are suitable for wilderness and mountain rescue operations.

Disaster Rescue Filter: Shows dogs that are identified as potential candidates for disaster rescue.



### Tools and Technologies

MongoDB: Chosen for its flexibility in handling unstructured data and robust support for CRUD operations through Python.

MongoDB's scalability and compatibility with Python made it an ideal choice for the model component of this application.

Python: The primary programming language used for developing the application, including the CRUD operations and dashboard components.

Dash: A Python framework used to build the web application dashboard. Dash was selected for its simplicity in creating interactive, web-based data visualizations and its seamless integration with Plotly for charting and data visualization.

Plotly: Used for creating dynamic, interactive charts that respond to the dashboard’s filters.



### Project Setup and Execution


### Prerequisites

Ensure you have the following installed:

Python 3.x

MongoDB

Required Python packages: dash, plotly, pymongo, pandas


### Installation

Clone this repository to your local machine:

bash

Copy code

git clone https://github.com/yourusername/grazioso-salvare-dashboard.git

cd grazioso-salvare-dashboard



### Install the required Python packages:

bash

Copy code

pip install dash plotly pymongo pandas

Set up your MongoDB instance and ensure it is running.

Import the CRUD module named AnimalShelterClass and pass in the necessary parameters (Username, Password, Host, Port, Database, Collection).



### Running the Application

Create your own Dash layout with widgets of your choice. Use PyMongo to create, read, update, and delete records in the collection.

Run the Dash app:

bash

Copy code

python app.py

Open a web browser and go to http://127.0.0.1:8050/ to view the dashboard.



### Example Filters

Unfiltered State: Displays all animals in the dataset.

Water Rescue Filter: Shows dogs that meet the requirements for water rescue training.

Wilderness / Mountain Rescue Filter: Displays dogs suitable for wilderness and mountain rescue.

Disaster Rescue Filter: Filters and displays dogs identified as potential candidates for disaster rescue operations.
