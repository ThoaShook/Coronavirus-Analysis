#### Coronavirus-Analysis
#####  Objective:
1. COVID-19 has have profound disruptive effects on the global ecconmy.Thousands of people have been infected. Schools are closed. Most activites are prohibited.Travels are baned,and people are panic..,etc
2. This study uses datasets from Kaggal, attempts to get the answers from questions that have arisen from the outbreak of the Covid-19:
    * What are current status of impacted countries: confirmed cases, death rate, and recovery rate?
    * Symptoms of Covid-19
    * Men or women, who are more susceptible to the virus?
    * What is the vulnerable age?
    * What can we learn from China - ground zero?
    * What are the future for USA, Italy, Spain, and India?
* Feature Engineering:
    * New feature is created using formula: 'Active cases' = 'Confirmed' - 'Recovery' - 'Death'.
    ![](Image/CountriesWithCovid19_df.png)
* Data Visualization:
    * Word Countries Map
        * Using Matplotlib to generate a World Countries Map with Covid-19.
        ![](Image/CountriesWithCovid19.png)
    * Plot a "Gender Distribution" bar chart using Matplotlib.pyplot.
        * Male are more succeptible to the virus than female.
        ![](Image/GenderDistribution.png)
    * Plot an "Age Distribution" histogram using Matplotlib.pyplot.
        * The average age of patient with the virus is 49 years old
        * The youngest patient is zero - 0 years old
        * The oldest patient is 96 years old
        ![](Image/ageDistribution.png)
    * Generate WordClouds using Natural Language Processing to extract texts from the 'Symptom' feature.
        * Cough
        * Fever
        * Discomfort breath
        * Vomiting
        * Diarrhea
        * Fatigue
        * Chills
        * Muscle pain,..etc
        ![](Image/Covid-19Symptom.png)
    * Create barh chart to rank countries from the most confirmed cases to the least.
        ![](Image/CountriesWithVirus.png)
    * 
     
    

    
    
    
  