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
       
        ![](Image/GenderDistribution.png)
         * Male are more succeptible to the virus than female.
    
    * Plot an "Age Distribution" histogram using Matplotlib.pyplot.
        
        ![](Image/ageDistribution.png)
        
        * The average age of patient with the virus is 49 years old
        * The youngest patient is zero - 0 years old
        * The oldest patient is 96 years old
    
    * Generate WordClouds using Natural Language Processing to extract texts from the 'Symptom' feature.
    
        ![](Image/Covid-19Symptom.png)
        
        * Patients with Covid-19 have these symptoms:
            * Cough
            * Fever
            * Discomfort breath
            * Vomiting
            * Diarrhea
            * Fatigue
            * Chills
            * Muscle pain,..etc
            

* Countries Trending Analysis:
    
    1. World Trends: 
        
        ![](Image/WorldTrend.png)
        
        - Key Takeaways:
           
        ![](Image/World_Key_Takeaways.png)

    2. China:
        - Using Index slicing to subset Region where the Country = 'Mainland China'
        - Use probability statistics and the 'group by' method to calculate the       number of confirmation cases, death rate, recovered rate, and active cases.
        - Create trending status using Matplotlib.pyplot
        
        ![](Image/Trend_in_China.png)
        
           
        ![](Image/China_KeyTakeaways.png)
        
    3. South Korea:
       
       - The same methods are applied as in China to generate trending status for the pandemic in South Korea
        
        ![](Image/SKorea_Trend.png)
        
            
        ![](Image/Skorea_info.png)

    4. Italy:
        
        ![](Image/TrendInItaly.png)
        
        - Key Takeaways:
            
            ![](Image/ItalyInfo.png)
    
    5. USA:
        
        ![](Image/TrendInUSA.png)
        
        - Key Takeaways:
         
            ![](Image/usaInfo.png)
        
    6. Spain:
        
        ![](Image/Spain_Trend.png)
        
        - Key Takeaways:
           
            ![](Image/spainInfo.png)
        
* World Trends Confirmed Cases by Day

    ![](Image/WordTrendConfirmedCases.png)

    - 
 
      

      
    

    
    
    
  