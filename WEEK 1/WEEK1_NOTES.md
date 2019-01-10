# Week 1: Getting Started with Data Science

## Data Science, Generating Value From Data[Engagement]

---

### Getting Value out of Data
DS to data into insights to inform hypothesis and provide information of a phenomenon.
    Big Data -> insight ---> actions --> data

Insight: data product of DS. 
    data + (analysis + questions) = insights
insights later turn into action

Data scientist need to be experts in a certain area so their insight are valuable.

__Why the increased interest in DS?__ 
Collect data in real time from multiple places has increased.
* Big Data
* Computing at Scale = New era of data science 
Big Data + Computing at Scale = New era of data science 

__How much data is Big Data?__
* Data can include any type of data from multiple devices.

__Scientific Data Management and Analysis__
* HPWREN: 30 TB of data annually
* MODIS: 219 TB of data annually
* Precision Medicine: 4 EB(10^18 bytes) in 2016
* data from a person with cancer is an hexabyte.

__How do we finde the connections?__
* Data driven methods
* scalable tools to analyze
* Try to see how everything is connected
* Proper use of data management

__Modern Data Scientist Skills__
* Programming
* Statistics/Probability
* Machine Learning
* Scalable Big Data Analysis

---

### Why Python for Data Science
__What is a Data Scientist?__
* Data Sciece is a team.
* Data Scientist are passionate for data, 
* relate to problems of data
* care about engineering solutions
* exhibit curiosity
* communicate with teammates

__Why do I need Python?__
* Easy to read and learn
* Vibran community
* Growing and envoling set of libraries
    * Data management
    * Analytical Processing
    * Visualization
* Aplicable to each step of DS

__Common Libraries__
* Jupyter
* Numpy
* Pandas
* Matplotlib
* Scikit-lean
* BeautifulSoup

### Soccer Data Analysis[Case Study]
The main idea is to take real datasets and obtain diferent results
* Form meaningul player groups
* Discover other player similar to athletes
* Form strong teams with analytics

__Understand the benefits__

Ask our selfs: *What insights do I expect to get?*

Insights:
* Better understandig and insights on
    * player strengths
    * enhancing performance
    * critical attributes for a players's performance
Base on this insights we will create actions:
Actions:
* Help the coach take decisions of the team

__Basic steps in a Data Science Project__
The process is a defined activity
1. __Acquire:__ 
    * Import raw data into your analytic platform
2. __Prepare:__ 
    * Explore and visualize
    * Perform data cleaning
3. __Analyze:__
    * Feature selection
    * Model selection
    * Analyze the results
4. __Report:__
    * Present our findings
5. __Act:__
    * Use them

__Data collection from diverse sources__
* Databases
    * Relational
    * No relational
* Text Files
    * CSV Files
    * Text files
* Live feeds
    * Sensors
    * Online platforms
        * Social networks
        * Wheater observations in real time

__Data ingestion to Analytics Platforms__
Pass the data into the platform, for this case is python.

__Data Preparation: Explore uing Statistics__
Apply different statistical models to see the summary of data.

__Data Cleaning__
* Why do we need to clean data?
    * Missing entries
    * Garbage values
    * Nulls

* How do we clean Data??
    * Remove the entries
    * Impute these entries with a conterpart
        * Average values of the coloumn
        * Assign 0, -1, etc

__Data Visualizations__
Is a way of representing data in a more summarized way.

__Analysis and Modeling__
* Supervised Learning
* Unsupervised Learning
* Semisupervised Learning

---

## How Data Science Happens [Engagement]

### How Data Science Happens
* DS Extracts value out of data based on a question
* It helps 
* Multidisciplinary craft that helps sicentist over a broad of questions to analyze data.

__DS Process__
* Sequence of steps
* Data engineering
    * Acquire
    * Prepare
* Computational DS
    * Analyze
    * Report
    * Act
At the end of the day is a programming analytical tool that helps analyze data.

### Asking the Right Question

__Define the problem__
Consist of making the basic ingredients to obtain value out of data. A problem well defined is a problem half solved.

__Assess the Situation__
This questions let get a better overview with the problems in mind.

* Risk
* Benefit
* Contingencies
* Regulations 
* Resources
* Requirements

__Define Goals__
* Objectives 
* Criteria

### Steps in DS
All steps will be use in the DS process.

__Acquire:__
* Identify datasets
* Retreive data
* Query data

__Explore Data__
* Understan nature of data
* Preliminary analysis

__Prepocessing__
* Clean 
* Integrate
* Package

__Analyze Data__
* Select analytias techniques
* Build models

__Communicate Results__
* Interpret
* Summarize
* Visualize
* Postproccess

__Apply results__
* Give value to the initial question

This whole process is an iterative tool.

---

## Acquire, Prepare, Analyze, Report, Act [Engagement]

### Step 1: Acquiring Data
__Where's the data__
* identify suitable data
* acquiere all avaible data
* local or remote
* data comes in multiple ways(structured or unstructured)

__Examples__

* traditional databases
* SQL and query browsers
* text files
* excel files

* Languages
    * ruby
    * Js
    * php
    * R
    * Octave
* Web services
    * remote data
    * XML
    * JSON
    * REST
    * WebSockets
* No SQL
    * MongoDB
    * Apache HBASE
    * Cassandra
    * Neo4J
    * CouchDB


### Step 2: [A] Exploring Data
__Why explore?__
Goal: understand your data

__Correlation Graphs:__ Explore dependencies between different data

__General trends:__ How data is progressing over time

__Outliers:__ Data points distance for other data points, this let us find check for errors in the data.

__Summary Statistics:__ Quantities that characterize a set of values, this often give a basic idea of the nature of it.

* _Mode:_ value that occurs more frequently
* _Median:_ Median of the location
* _Mean:_ Average of data
* _Range & STDEV:_ How data is spread

__Visualize Data__
* _Heat map:_ Gives ideas of hot spots
* _Histograms:_ Distribution of data
* _Box Plots:_ Also displays how data is distributed
* _Line graphs:_ How data is changing overtime
* _Scatterplots:_ Correlation of data


### Step 2: [B] Pre-processing Data
Clean + Transform

__Messy data__

* inconsistent data types
* duplicate records
* missing values
* invalid data
* outliers

__Addressig Data Quality Issues__

* Remove data with missing values
* Merge duplicate records
* generate best estimate for invalid values
* remove outliers

__Getting data in shape__

Also known as Data mungin, data wrangling and data preprocessing

__Operations__
* _Scaling:_ Change range of values(normalization) 
* _Dimensionality reduction:_ eliminates irrelevant features(principal component analisys) 
* _Transformation:_ Agregate data with less variability or noise removal/also know as smoothing data
* _Data Manipulation:_ capture specific segments grouping them according to a certain group
* _Feature selection:_  
    * _Remove features:_ remove redundant features
    * _Combine features:_ correlate data without negativaly affect data
    * _Add features:_ add new ways of calculation, example tax

### Step 3: Analyze Data
__Model Building__

Inut data -> Analysis Techniques -> Model -> Model output


__Categories of Analysis Techniques__

* _Classification:_ Predict a category
* _Regresion:_ Predict a numeric value
* _Clustering:_ Organize similar items into groups
* _Association Analysis:_ Find ruels to capture associations between items
* _Graph Analytics:_ Use graph structures to find connections between entities
* _Modeling:_ Select Technique -> Build Model -> Validate Model


__Evaluation Techniques__
* _Clasification vs Regresion:_ predicted value vs correct value
* _Clustering:_ Examine if the clusters make sense
* _Association Analysis & Graph Analysis:_ investigate the outpus and validate the value. Then repeat the analysis with mmore data, take a deeper dive and finally act on results.


### Step 4: Reporting Insights

__Communicate Results__

__What to present?__
* Determinate what part of analysis go first(piramyd structure)
* What are the main results
* How does the results are compared to the succeed criteria
* The biggest labor is to make hard data into easy stories

__How to present?__

* All kind of graphs area good
* Some visualization tools
    * R
    * Python
    * D3JS
    * Google Developers Charts
    * Tableau
    * TimelineJS

### Step 5: Tunning Insights into Action

Connect your result with scientific questions

Results -> Purpose

### Conclusion
Apply this process into programming tools so data can gain more valuable insights