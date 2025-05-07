# Discourses of Energy-Saving Delay - Bachelor Thesis at Öko-Institut 

 This repository contains the code and data for the bachelor thesis **'Discourses of Energy-Saving Delay'**. This thesis analyses how narratives around energy-saving delay were constructed on Twitter during Germany's 2022-2023 energy crisis. Narratives and engagement metrics are analysed, sentiment distribution illustrated and recurring linguistic patterns visualised using word clouds.


## Table of Contents
- Overview
- Project Structure
- Requirements
- Installation
- Usage
- Data
- Results
- Contact
- License
- References
 
 
 
## Overview

 The bachelor thesis aims to understand the narratives underlying energy-saving obstruction behaviour. Twitter data is analysed to identify and visualise discourses related to energy-saving delay. Based on the 'Discourses of Climate Delay' framework by Lamb et al. (2020), categories were developedand and applied manually.
 
**The main objectives in the thesis are:**
- to classify tweets according to delay narrative categories
- to explore engagement patterns and dominant themes
- to provide insights for future communication strategies to improve public acceptance of energy-saving and transition

The core analysis is implemented in the Visual Studio Code 'Discourses_of_energy_delay.ipynb'
 
 
## Project Structure
 
.

├── Data/new_categories_corpus_tweets_energy_saving_random_sample_1000.csv

├── Discourses_of_energy_delay.ipynb

└── README.md

- **Data/**: Folder that contains tweet data, including meta data and categorisation
- **Discourses_of_energy_delay**: Main notebook for data analysis and visualisation


## Requirements
- Python 3.13.2
- Visual Studio Code
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- wordcloud
- vadersentiment


## Installation
Install dependencies with:

pip install pandas numpy matplotlib seaborn nltk wordcloud vadersentiment


## Usage
1. **Clone the repository:**
   git clone https://github.com/Emcha16/Bachelorarbeit_Discourses_of_Energy-Saving_Delay.git
     cd Bachelorarbeit_Discourses_of_Energy-Saving_Delay
2. **Add data:**
   - Place the data files (e.g. CSVs with tweets) in the Data/ folder
3. **Open the environment:**
   - Start Visual Studio Code
   - Open 'Discourses_of_energy_delay.ipynb' and run the cells step by step
4. **Adjust parameters:**
   - If necessary, update file paths or parameters in the environment to match your data structure


## Data
**Note:** The data used for the analysis is a sample of 1,000 tweets from the dataset used in Loschke et al. (2025) at the Öko-Institut. Please contact the author or the Öko-Institut for details or use your own dataset in the required format.


## Results
The Python script produces:
- An overview of the data, including data types
- Statistics and visualisation of narrative categories within the Twitter data
- Insights into engagement metrics, dominant discourses, and linguistic patterns


## Contact
For questions, please contact:
- Emcha16


## License
This project is for academic and research purposes. Please cite appropriately if you use or adapt the code. 


## References
1. Lamb, W. F., Mattioli, G., Levi, S., Roberts, J. T., Capstick, S., Creutzig, F., Minx, J. C., Müller-Hansen, F., Culhane, T., & Steinberger, J. K. (2020). Discourses of climate delay. Global Sustainability, 3, e17. https://doi.org/10.1017/sus.2020.13
2. Loschke, C. S., Braungardt, S., & Rieger, J. (2025). What motivates and demotivates energy savings in times of crisis? – An argument mining analysis using X/Twitter data. https://doi.org/10.21203/rs.3.rs-4544117/v1






  
