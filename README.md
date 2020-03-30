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
        ![](Image/Covid-19CasesperCountry.png)
* Countries Trending Analysis:
    1. China:
        - Using Index slicing to subset Region where the Country = 'Mainland China'
        - Use probability statistics and the 'group by' method to calculate the       number of confirmation cases, death rate, recovered rate, and active cases.
        - Create trending status using Matplotlib.pyplot
        ![](Image/TrendInChina.png)
        - Keys Takeaway:
            * Number of confirmed cases continues to grow sharply from 01/22/20 to the end for Feburary.It then starts level off the first week of March
            * Number of Deaths are steadily increasing from 1/22/20 - 3/14/20. It continues increading even when the confirmed cases are stablized. It can be inferred that the previous confirmed cases were not be able to recovered.
            * The recovery rate in the first 10 days is zero.But after that it increase sharply, and continue to grow. China did very well in fighting the virus
            * Active cases went down sharply from 2/21 - 3/05/20.This is very easy to explain. Since the confirmed cases are stable, the recovery rate is increase sharply; therefore active cases drop dramatically.
            * China did very good job in handling the pandemic. Since the first week of March, confirmed cases are stablized, recovered rate are shot up, active cases drop sharply. The other countries should learn the ways China handles the crisis.
            * In China, since 03/05/20, Active Cases and Recovery Percentage is 22.82%, 73.32% respectively and Death Rate is 3.86%.
    
     
    

    
    
    
  