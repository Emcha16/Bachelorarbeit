Discourses of Energy-Saving Delay - Bachelor Thesis at Öko-Institut 

This repository contains the code and data for the bachelor thesis 'Discourses of Energy-Saving Delay'. This thesis analyses how narratives around energy-saving delay were constructed on Twitter during the energy crisis 2022-2023 in Germany. Thereby, narratives as well as engagement metrics are analysed and portrayed, sentiment distribution illustrated and recurring linguistic patterns in word clouds visualised.


Table of Content
- Overview
- Project Structure
- Requirements
- Usage
- Data
- Results
- Contact
- License
- References
 
 
 
Overview
The bachelor thesis aims to understand the narratives underlying energy-saving obstruction behaviour. Therefore, Twitter data is analysed to identify and visualise discourses related to energy-saving delay. The development of categories and the following categorisation was performed manually beforehand. The categories are based and inspired by the 'Discourses of Climate Delay' framework by Lamb et al. (2020).
The main objectives in the thesis are:
- to classify tweets according to delay narrative categories
- to explore engagement patterns and dominant themes
- to provide insights for future communication strategies to improve public acceptance of energy-saving and transition

The core analysis is implemented in the Visual Studio Code "Discourses_of_energy_delay.ipynb"
 
 
 
Project Structure
 
.

├── Data/new_categories_corpus_tweets_energy_saving_random_sample_1000.csv

├── Discourses_of_energy_delay.ipynb

└── README.md

- Data/: Folder that contains tweet data, including meta data and categorisation
- Discourse_of_energy_delay: Main notebook for data analysis and visualisation


Requirements
- Python 3.13.2
- Visual Studio Code
- pandas
- numby
- matplotlib
- seaborn
- nltk
- wordcloud
- vadersentiment

     pip install pandas numpy matplotlib seaborn nltk wordcloud vadersentiment


Usage
1. Clone the repository:
   git clone https://github.com/Emcha16/Bachelorarbeit_Discourses_of_Energy-Saving_Delay.git
     cd Bachelorarbeit_Discourses_of_Energy-Saving_Delay
2. Add data:
   - place the data filed (e.g. CSVs with tweets) in the Data/ folder
3. Open the environment:
   - start Visual Studio Code
   - open "Discourses_of_energy_delay.ipynb" and run the cells step by step
4. Adjust parameters:
   - if necessary, update file paths or parameters in the environment to match your data structure
  

Results
The Python script produces:
- an overview of the data, including data types
- statistics and visualisation of narrative categories within the twitter data
- insights into engagement metrics, dominant discourses, and linguistic patterns







  
