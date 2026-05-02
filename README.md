AeroAnalytics - Streamlit Aviation Data Visualization & Aircraft Detection
Overview
AeroAnalytics is a Streamlit web application designed for aviation data visualization and aircraft detection using Machine Learning.  
The project combines interactive dashboards, airport and flight route analysis, aircraft specifications, and a machine learning detection module.
This application helps users explore aviation-related data in a clear and visual way while demonstrating how data science and machine learning can be applied in the aeronautical field.
Project Objective
The main objective of this project is to build an interactive aviation analytics platform that allows users to:
Visualize airport and aircraft route data
Explore flight trajectory information
Analyze aircraft specifications
Detect or identify aircraft using a machine learning model
Present aviation data through a simple and professional Streamlit interface
Main Features
Interactive Streamlit web interface
Airport data visualization
Aircraft flight route visualization
Aviation dataset exploration
Aircraft specifications analysis
Machine learning-based aircraft detection
Clean dashboard layout for aviation analytics
Simple deployment on Streamlit Cloud
Technologies Used
Python
Streamlit
Pandas
NumPy
Scikit-learn
Matplotlib / Plotly
Machine Learning
Data Visualization
Aviation Data Analysis
Project Structure
```text
AeroAnalytics/
│
├── models/
│   └── machine_learning_model_files
│
├── README.md
├── aircraft_specs.csv
├── flights_aero.csv
├── logo.png
├── requirements.txt
└── testapp2324.py
```
Files Description
File / Folder	Description
`models/`	Folder containing the trained machine learning model files
`testapp2324.py`	Main Streamlit application file
`aircraft_specs.csv`	Dataset containing aircraft specifications
`flights_aero.csv`	Dataset containing airport and flight route information
`logo.png`	Logo used in the Streamlit interface
`requirements.txt`	List of required Python libraries
`README.md`	Project documentation
Datasets
The project uses aviation datasets related to aircraft specifications, airport information, and flight routes.  
These datasets are used to generate visual insights and support the machine learning detection system.
Main Data Used
Aircraft specifications
Airport and route data
Flight trajectory information
Features used for aircraft detection
Machine Learning Module
The machine learning part of this project is used to detect or identify aircraft based on available input features.  
The model analyzes aviation-related data and returns a prediction that can support aircraft recognition or classification.
This demonstrates the use of machine learning in aeronautical applications, especially for data-driven aircraft analysis.
How to Run the Project
1. Clone the repository
```bash
git clone https://github.com/anas-iazza/AeroAnalytics.git
```
2. Open the project folder
```bash
cd AeroAnalytics
```
3. Install the required libraries
```bash
pip install -r requirements.txt
```
4. Run the Streamlit application
```bash
streamlit run testapp2324.py
```
After running the command, the application will open in your browser.
Streamlit Cloud Deployment
This project can also be deployed on Streamlit Cloud by connecting the GitHub repository and selecting the main file:
```text
testapp2324.py
```
Expected Result
The user can access a web dashboard that displays aviation data, flight routes, airport information, and aircraft-related visualizations.  
The application also includes a machine learning component for aircraft detection or identification.
Skills Demonstrated
Python programming
Streamlit web application development
Data visualization
Aviation data analysis
Machine learning integration
Dataset processing
Dashboard design
Deployment preparation for Streamlit Cloud
Future Improvements
Improve the user interface design
Add more interactive maps for airport and flight route visualization
Improve the machine learning detection model
Add model performance metrics
Add filters for aircraft type, airport, country, and route
Add downloadable reports
Deploy a stable online version of the application
Author
Anas Iazza  
Aeronautical Engineering and Space Technologies Student
License
This project is developed for academic and learning purposes.
