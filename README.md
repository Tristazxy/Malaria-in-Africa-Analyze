# Malaria_in_Africa_Jornalism124_Final_Report
This repository is mainly through the dataset that report about the malaria in Africa to analysis about the relationship between the malaria cases with the local environment condition.
## Story Pitch
### Background
Malaria has long been one of the most deadly diseases on the African continent. With approximately 95% of malaria cases in Africa each year and a subsequent death rate of up to 96%, there has never been a way to control malaria. Until 2015, a Chinese Nobel Laureate in Physiology or Medicine Youyou Tu found artemisinin, a derivative of anthocyanin that is the fastest-acting drug against Plasmodium falciparum. Malaria is a disease that can go from infection to death very quickly, so prevention malaria and timely follow-up therapyare especially important. This malaria of Africa table includes the number of reported infections in each country in Africa from 2007 to 2017, also includes about people who have safely managed drinking water services or sanitation and other informations. By analysis this table can determine whether the invention of penicillin was effective in controlling malaria for African countries.

source link: https://www.kaggle.com/datasets/lydia70/malaria-in-africa?resource=download

### Interview Contect Info
1) Peter Singer, The Life You Can Save Orgnization Founder, also a Professor at University of Melbourne and University of Oxford
	* Phone number: 609-258-2202
	* Email: psinger@princeton.edu
	* The life you can save organization distributes mosquito nets and insecticides to 36 countries and has been working to combat the spread of malaria.
2) Lawrence Tabak, Performing the Duties of the NIH Director
	* Phone Number: 301-496-7322 
	* Email: lawrence.tabak@nih.gov
	* Lawrence Tabak is the director for National Institution Health. This government agency will provide malaria awareness and recent malaria protection precautions.
    
## Data Analysis and Visulization

### Note：No additional data cleaning is required for the table's data

#### Q1:From 2007 to 2017, which are the countries with the highest malaria case report each year?

First I download the data to Excel, since I want to find out the each years' highest report, I select each years's malaria case report column，and sort by a descending order. I also highlighted the highest report case for each year and the country's name.

![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/2.png)
![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/3.png)
![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/1.png)

From these charts we conclude that there is an overall upward trend in the number of people with malaria each year, with the exception of 2007 and 2008, congo,Dem,Republican has been the most reported country for malaria, with nearly nine times more people getting malaria in the country from 2009 to 2017. 2016 was the year with the highest number of malaria cases in congo,Dem,Republican with 16,821,130 cases.

#### Q2:By using the Choropleth map show the malaria severity of countries in africa.

In this question I want to use data visulization to intuitively observe the extent to which each country in Africa is affected by malaria.

I use datawrapper to create a choropleth map, first I need to select my map, in this case I chose Africa. Then, I upload my data for visulization,by selecting the colunm of the incidence of malaria, the map automatically generated. In anotate, I clicked the map label botton for show up countries name, I also did the continouse type to make the infection region more clear.

Link: https://datawrapper.dwcdn.net/bowgO/1/

![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/4.png)

The map shows that the southwest and central regions are at the highest risk of malaria, with the highest proportion of malaria. The northern and southern parts of Africa have very little chance of contracting malaria, and Egypt has a near zero risk. a black and purple section next to the Democrtic republic of the congo is Rwanda, which has a near maximum chance of contracting 550.

#### Q3: Find out the average Incidence of malaria in all Africa countries in 2013 and 2017.

In this quetsion, I select 2013 and 2017 as comparison is becasue the artemisinin 

![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/5.png)
![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/6.png)

According to the chart it can be seen that Incidence of malaria in 2017 is significantly lower compared to 2013, the average of Incidence of malaria for all countries in Africa in 2013 was about 185 people per 1000 people will be infected with malaria, by 2017, the average of 176 people per 1000 people for all countries in the Americas would get malaria. This means that cyanobacteria does help with malaria. The data shows that from 2013 to 2017, 9 out of 1000 people were saved from malaria.

#### Q4:What’s the population trend for Congo, Dem. Rep.

since we know from Q1 that COngo, Dem. Rep is the country with the highest malaria report for 9 years from 2009 to 2017, therefore their population trend will show how badly the malaria has effect this country. I compared both rural and urban pupulation by using pivot table, I put the year as the row and country name as the colunm. Then I put the main data of rural and urban population to the value. After that I create a line graph for visulize the population trend for Congo, Dem , Rep.

![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/8.png)
![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/7.png)

The graph illustrate the population for urban has been increase, the rural population have a contrary trend. By notice those two line start their change form 2011, after 2014 the line becomes slightly steeper. By predic the reason for this phenomenon, the access for safetly water and sanitation is essential, the city must have more resorces compare with rural, so the rural population will be more decrease if there is lack of help for them.

#### Q5:For people who get malaria in africa, Which countries have good treatment for children with the disease and pregnant women？

I use excel to solve this question, First I created a column for calcualate the people who got malaria but with a good treatments. The formula is by select the children with the disease percentage times the malaria report then add the pregnant women who have disease times the malaria report. After get the result for people who can receive good treatment ater get the disease, by using sort to descending the colunm. 
![image](https://raw.githubusercontent.com/Tristazxy/Malaria-in-Africa-Analyze/main/images/9.png)

Uganda, Mozambique,Burundi, Ghana,and Nigeria are the top five countries with good treatment for people who effect the malaria. Uganda performed particularly well, as it saved more sick children and pregnant women in two consecutive years in 2015 and 2016, respectively. Notably, uganda saved nearly 2 million more people than Mozambique, which came in second place. 

## Additional Resources:

[What is malaria?](https://www.cdc.gov/malaria/about/faqs.html#:~:text=Malaria%20is%20a%20serious%20and,humans%3A%20Plasmodium%20falciparum%2C%20P.)

This resource provides information on the transmission routes and viral principles that cause malaria. It also explains which populations are susceptible to infection and the symptoms of infection. This site was created to prevent and control dangerous diseases. This resource is helpful for the story because it can provide more detail on the relevance of malaria to our lives, proving that malaria is not just rampant in Africa, but can also affect our lives if we don't help control it.

[Is Africa losing ground in the battle for water and sanitation?](https://www.washingtonpost.com/politics/2022/01/28/is-africa-losing-ground-battle-water-sanitation/)

This article in Washington reported that the water quality in Africa is getting worse under the extreme shortage of water, because of the lack of water, so the toilets are not available, leading to the growth of bacteria and viruses. Because my story data has information about water sources and sanitation across Africa, this story can help understand the reasons for Africa's water scarcity. 
