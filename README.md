# \# 🏅 Olympics Data Analysis Project



This is an interactive data analysis project built using \*\*Python\*\*, \*\*Pandas\*\*, \*\*Machine Learning\*\*, and \*\*Streamlit\*\* to explore and visualize \*\*Olympics historical data\*\*.



## \## 📊 Project Highlights



The application provides insights through four main sections:



1\. **\*\*Medal Tally\*\***

&nbsp;  - Explore medal counts by year and country

&nbsp;  - Select any country/year combination for filtered results



2\. **\*\*Overall Analysis\*\***

&nbsp;  - Key statistics: total editions, cities, sports, events, athletes, nations

&nbsp;  - Line charts showing trends of participation and events over the years

&nbsp;  - Heatmaps of events by sport and year

&nbsp;  - List of the most successful athletes overall or by sport



3\. **\*\*Country-wise Analysis\*\***

&nbsp;  - Line chart of a selected country's medal tally over the years

&nbsp;  - Heatmap of sports the country excels in

&nbsp;  - Top 10 athletes from that country



4\. **\*\*Athlete-wise Analysis\*\***

&nbsp;  - Distribution of athlete ages overall and by medal type

&nbsp;  - Age distribution of gold medalists across various sports

&nbsp;  - Height vs Weight plots by sport, with medal and gender styling

&nbsp;  - Line chart comparing male vs female participation over time



---



### \## 📁 Folder Structure

Olympics data analysis/

├── app.py # Main Streamlit application

├── helper.py # Contains data analysis and plotting helper functions

├── preprocessor.py # Cleans and preprocesses the dataset

├── athlete\_events.csv # Main Olympic dataset

├── noc\_regions.csv # Mapping of NOC codes to region names

├── requirements.txt # List of Python dependencies

├── procfile.txt # For deployment on Heroku

├── setup.sh # Deployment setup script

├── .gitignore # Specifies untracked files

└── README.md # Project documentation







---



#### \## 🧠 Technologies Used



\- \*\*Python 3\*\*

\- \*\*Pandas \& NumPy\*\*

\- \*\*Matplotlib \& Seaborn\*\*

\- \*\*Plotly Express \& Figure Factory\*\*

\- \*\*Streamlit\*\* (for interactive UI)

\- \*\*Heroku\*\* (for deployment)



---



### \## ⚙️ How to Run Locally



**1. Clone the repository:**

&nbsp;  ```bash

&nbsp;  		git clone https://github.com/yourusername/olympics-data-analysis.git

&nbsp; 		cd olympics-data-analysis





**2.(Optional but recommended) Create a virtual environment:**



bash

&nbsp;		python -m venv venv

&nbsp;		source venv/bin/activate  # On Windows: venv\\Scripts\\activate





**3.Install dependencies:**



bash

&nbsp;		pip install -r requirements.txt





**4.Run the Streamlit app:**



bash

&nbsp;		streamlit run app.py





#### 🚀 Deployment

This app can be deployed using Heroku or Streamlit Cloud.



If deploying on Heroku, make sure you include:



&nbsp;		. Procfile



&nbsp;		. setup.sh



&nbsp;		. requirements.txt







#### 📦 Data Source

&nbsp;		Kaggle - Olympic History Dataset









