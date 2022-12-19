# CS340

README
About the Project
The project is a dashboard that allows users to view and filter data about animal rescues. The dashboard is built using the Dash framework, which is a library for creating web-based data visualization applications. The data is stored in a MongoDB database and can be filtered using a radio button. The dashboard also includes a data table to display the filtered data and a map to show the location of the rescue. The project is intended to provide a user-friendly interface for exploring and analyzing animal rescue data.

Motivation
The motivation for this project is to provide a tool for animal rescue organizations to better understand their data and make more informed decisions about their operations. By visualizing the data in a user-friendly dashboard, organizations can quickly and easily identify trends and patterns in their rescue data, such as the types of animals they rescue most often and the locations where rescues are most common. This information can help organizations optimize their resources and improve their rescue efforts. Additionally, the dashboard can be used by individuals interested in animal rescue data to learn more about rescue trends and patterns.

Getting Started
To get started with this project, you will need to install the following dependencies:
Dash
Dash Leaflet
Dash Core Components
Dash HTML Components
Plotly
Dash Table
Numpy
Pandas
Pymongo
Bson
You can install these dependencies using pip or conda by running the following commands:
PIP
pip install dash dash-leaflet dash-core-components dash-html-components plotly dash-table numpy pandas pymongo bson
CONDA
conda install dash dash-leaflet dash-core-components dash-html-components plotly dash-table numpy pandas pymongo bson

Once the dependencies are installed, you can run the Dash app by executing the following command in your terminal:

python app.py

This will start the Dash server and open the app in your web browser. You can then interact with the app by selecting different filter options and exploring the data in the data table and map.
 
 
Usage
To use the Dash app, open it in your web browser by running the python app.py command in your terminal. The app will display an image, some text, a radio button to filter the data, and a data table.
To filter the data, select one of the options in the radio button (Water Rescue, Mountain or Wilderness Rescue, Disaster or Individual Tracking, or Reset). This will update the data table to show only the records that match the selected filter type.
The data table displays all of the available data about the animal rescues, including the type of animal, the date of the rescue, and the location of the rescue. You can sort the table by clicking on the column headers, and you can page through the data by using the controls at the bottom of the table.
The map on the right side of the dashboard shows the location of each rescue. The map is interactive, so you can zoom in and out and pan around to explore the data in more detail. The markers on the map represent the location of each rescue, and the color of the marker indicates the type of animal that was rescued.

Contact
Tyler Jackson
