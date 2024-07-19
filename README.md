# Webscraping using Beautiful Soup and Splinter

The first part of this challenge uses Browser imported from Splinter to visit the mars news website. Once there, inspecting the page elements reveals the details needed to extract the artcile titles and previews. Then Beautiful Soup is used to extract the chosen data. The Beautiful Soup extract file is then parsed into a list using a for loop to store each title/preview dictionary pair.  

The second part of the challenge returnst to the Mars site and uses a similar process extract the temperature data stored in the table on the site. Splinter and Beautiful Soup are used to extract the data and a for loop is used to create a list of lists storing the following data points:  

id: the identification number of a single transmission from the Curiosity rover  
terrestrial_date: the date on Earth  
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars  
ls: the solar longitude  
month: the Martian month  
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)  
pressure: The atmospheric pressure at Curiosity's location  

Using Pandas, a dataframe is created to hold this data. Once the data is cleaned, ensuring the data types are correct, the analysis and visualizations can begin. These are the project data analysis requirements:  

How many months exist on Mars? (nunique)  
How many Martian (and not Earth) days worth of data exist in the scraped dataset? (count)  
What are the coldest and the warmest months on Mars (at the location of Curiosity)? (mean to find average for each month)  
Plot the results as a bar chart.  
Which months have the lowest and the highest atmospheric pressure on Mars? (mean to find average for each month)  
Plot the results as a bar chart.  
About how many terrestrial (Earth) days exist in a Martian year?  
Visually estimate the result by plotting the daily minimum temperature.  
Export the DataFrame to a CSV file.  

![image](https://github.com/user-attachments/assets/1cee89c8-9793-4e32-8679-ad32ee2c4608)


![image](https://github.com/user-attachments/assets/ef39f3fb-47c1-4c6a-be2e-e311fae7ad56)


![image](https://github.com/user-attachments/assets/34d0fb5b-4db8-4ccf-a265-6d7167c63c66)
