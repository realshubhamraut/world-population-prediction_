# Population-Prediction-System

Application Link: https://tulasinnd-population-prediction-system-population-app-x6rrby.streamlit.app/

Application Demo Video Link: https://www.linkedin.com/posts/tulasi-n-49b6111b0_population-prediction-system-view-application-activity-7036599665772957696-Jc1X?utm_source=share&utm_medium=member_desktop

Skills Required: Python, ML, Streamlit, Pandas, Sklearn

This code is a population prediction system that uses polynomial regression to predict the population of a selected country for a given year. The code imports two datasets: "Countries_Population_final.csv" which contains the population data of various countries from 1960 to 2021, and "Countries_names.csv" which contains the names of the countries.

The code uses Streamlit to create a dashboard interface where the user selects a country and enters a year. If the year entered is numeric, the code trains a polynomial regression model using the population data of the selected country from 1960 to 2021. The model is then used to predict the population of the selected country for the given year. The predicted population and the accuracy of the model (R2 score) are displayed on the dashboard.

The predicted population and the previous year's population data are also plotted using Plotly. The predicted population for the given year is represented by a star on the plot.

The code requires the following libraries to be installed: pandas, numpy, scikit-learn, streamlit, plotly, and numerize.




