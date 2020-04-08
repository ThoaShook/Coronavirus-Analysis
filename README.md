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
        
        ![](Image/Coronavirus_WorldMap.png)
    
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

    ![](Image/ConfirmedCasesInChina_SKorea_USA_Italy_Spain.png)

    - Key Takeaways:
     
        * At the begining of February the confirmed cases in China, S.Korea, Italy, USA, & Spain are 11,871;12; 0; 6; and 1 respectively
        * Confirmed cases In China rise steadily and in mid Feb, it seems Chinal has control over the pandemic. The confirmed cases of China are level off from mid Feb. At 04/01/20 confirmed cases are 81,555 cases
        * Meanwhile at Mar 15th confirmed cases in USA start to increase suddenly, and at the beginning of April its confirmed cases are 213,372 cases
        * South Korea has handled the pandemic very well. At 04/01/20 confirmed cases in South Korea are 9,887 cases
        * Confirmed cases in both Italy and Spain are increasing, at 04/01/20 the confirmed cases in both countries are 110,574 and 104,118 respectively 
        * We should take notes and learn how China and South Korea handle the pandemic !
      
* World Trends Death Cases by Day

    ![](Image/DeathsInCountries.png)
    
    - Key Takeaways:
    
        * The death rate in China grow steadily while the other countries remain almost zero cases. However, in March 1st, the death rate in China is leveled off and by April 1st, number of deaths in China is 3,312.
        * South Korea does very well in handling the pandemic, by April 1st, the number of deaths is 165 ! Very impressive!
        * The death rate in USA, Italy, and Spain all increase abruptly in March, by the first day April, the number of deaths by these countries are 4757; 13,155; and 9387 respectively
        * For the US, Italy, and Spain the death rates grow exponentially from the first day of March for Italy and middle of March for both Spain and USA. It can be infered that the virus may have been in these countries and spreading quietly among people without being detected or tested or awared and at a very early date as early as in China because travel ban hasn't applied earlier. These causes all together explain quite well the death rates in these countries.
    
* World Trends Active Cases by Day

    ![](Image/TrendsInActiveCasesInCountries.png)
    
    - Key Takeaways:
    
        * China and South Korea have very low number of active cases, by April 1st, the active cases in both are 1995 and 4155 respectively
        * USA has a continuing rising active cases, by April 1st, the number of active cases in the USA is 200141 cases
        * Both Italy and Spain have increasing active cases but by far a lot less than the USA. The active cases for these two countries by April 1st are 80572 and 72084 respectively
        * Even though the confirmed and actives cases are high in the USA, the death rate so far is less than that of Italy and Spain. Italy and Spain should have taken a look at how the USA handles the pandemic.
    

      
    

    
    
    
  