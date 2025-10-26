
# Antidepressant Prescribing Trends in England (2012–2024)
This study examines antidepressant medication prescribing patterns and costs in England's NHS.  
I have merged data from two trustworthy sources: OpenPrescribing (Oxford University) aggregated NHS data (2020–2024) and Prescription Cost Analysis (PCA) NHS Digital (2012–2018).  
2019 data are not available due to lack of data on this year on both of the sources.

# Method
1. Data was used from annual antidepressant prescriptions and costs (2012–2024) from NHS Digital and the NHS Business Services Authority.

 2. Pandas was used to import the datasets into Python for analysis and cleaning.

 3. I eliminated any missing or duplicate entries, renamed columns for clarity, and formatted the text and date columns appropriately.

 4. To determine the total number of prescribed items and the overall NHS cost, data were grouped by year.

 5. I divided the total cost by the total number of items to create an extra column that displays the average cost per item.

 6. A complete timeline from 2012 to 2024 was created by combining data from several years.

 7. I visualised the results using Matplotlib, which included comparisons of annual NHS costs and prescription trends.
    
# Conlusion 
The number of antidepressant items dispensed increased from approximately 50 million in 2012 to approximately 92 million in 2024. Due to the switch between PCA and OpenPrescribing sources According to the results, antidepressant use is rising in England while NHS costs are falling. This trend can undoubtedly be attributed to the use of generic medications and price reductions. 
