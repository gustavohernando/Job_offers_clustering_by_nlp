# Job_offers_clustering_by_nlp
![imagen](src\utils\01 Glassdoor Png.png)

## Summary:  
* Academic project developed for educational purpose as a summary of the skills developed during the Machine learning module in the Data Science Bootcamp in The Bridge. 

* This work is a continuation of a previous project(Exploratory analysis of data roles in Spain published on Glassdoor) where I scrapped Glassdoor for elaborating a Job roles data set, taking advantage of this data set In this project we are going to cluster these job offers, using natural language processing tools (NLP) to determine if the job offers to match the title with the required skills,  reason, why we are going to use the job, offers description without tags, as a Non supervised model. 

## Scope
* workflow
    1. Exploratory Data Analysis.
    2. Preprocessing data. 
    3. Vectorizacion 
        * CountVectorizer
        * Time TfidfVectorizer
    4. Applying CLusterazation models
    5. Visualing Clusterization
    6. Applying Textacy & Spacy
    7. Model
    
* Data Sources/ Web scrapping realized with this features. 
    * Data roles evaluated:
        * Business Analyst
        * Data Analyst
        * Machine Learning Engineer
        * ML Engineer
        * BI Analyst
        * Data Scientist
        * Data Architect
        * Data Engineer
    * Country: Spain 
    * Time frame: 20-07-2021 / 27-07-2021   
    * Job offers browser:  wwww.glassdoor.com 

## Deliverables
* A_Libreria_generacionBDsGlassdoor.py -> main file, where all the functions used in the project are allowed 
    
* Files
    1. src/: Source code
    2. src/utils: auxiliary functions and extra modules. 
    3. src/data/raw: Data set
    4. src/data/processed: Data set processed. 
    5. src/notebooks: notebooks de limpieza, procesado, EDA y modelos de Machine Learning.
    6. src/train.py: N/A
    7. src/model: predictive model generated. 
   
## Used libraries
* Data handling: 
    * [Numpy](https://numpy.org/doc/)  
    * [Pandas](https://numpy.org/doc/)
    * [Time](https://docs.python.org/3/library/time.html)
    * [datetime](https://docs.python.org/3/library/datetime.html)
    * [re](https://docs.python.org/3/library/re.html)
    * [json](https://docs.python.org/3/library/json.html)
    * [matplotlib](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
    * [seaborn](https://seaborn.pydata.org/)   

* Working directory management: 
    * [os](https://docs.python.org/3/library/os.html)

* Web scrapping: 
    * [Selenium](https://www.selenium.dev/)
    * [joblib](https://joblib.readthedocs.io/en/latest/)
 
    
* Machine learning & NLP
    * [scipy](https://www.selenium.dev/)
    * [sklearn](https://scikit-learn.org/stable/index.html)
    * [nltk](https://www.nltk.org/)


## Tools: 
* [PyCharm](https://www.jetbrains.com/pycharm/)
* [Jupyter-lab](https://jupyter.org/)

## Author:
* Gustavo Hernando - <gahs40@gmail.com>

## Tutored by:
* Daniel Ortiz - <daniel@thebridgeschool.es>
* Ander Arana - <ander@thebridgeschool.es>
