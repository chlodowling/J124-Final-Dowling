# An Analysis of Organ Transplants in Hawaii by Racial/Ethnic Group 
### By Chloe Dowling
description 
Accessibility of organ transplants?

## Story Summary 
WEDNESDAY 
Mention what UNOS stands for

## Sourcing 
### People
* Felicia Wells-Williams, Director of Clinical Services at Legacy of Life Hawaii
    * Wells-Williams is the Director of Clinical Services at Legacy of Life Hawaii, a nonprofit organization in Hawaii dedicated to organ and tissue recovery for transplant. As Felicia has worked in the organ transplant industry in Hawaii for almost 30 years, I would want to talk to her about the implications of race and ethnicity in receiving an organ for transplant. I would be currious to know if she has observed changes in the last 30 years regarding accessibility to organ transplants based on race. Felicia would provide an expert perspective.
    * I would reach out to Felcia Wells-Williams through her [LinkedIn](https://www.linkedin.com/in/feliciawellswilliams/) account as her email and phone number are not discoverable via Google. 
* Milton Arellano, Hawaii resident and organ transplant recipient
    * Arellano is a kidney transplant recipient, currently residing in Waipahu, Hawaii on the island of Oahu. Arellano's transplant surgery occured in December of 2022 in San Fracisco, California. While his surgery did not occur in Hawaii, I would be curious to learn about his experience of waitting for a kidney in Hawaii and why he ultimately received a kindey in California instead of Hawaii. I would also hope to ask him how accessible the organ transplant process was for him. Milton's personal experience would add an emotional and insider perspective to the story. 
    * Phone number: (808) 391-1193
    * Email: arellano808@gmail.com
    * I discovered Arellano's kidney transplant story from [this Star Advertiser article](https://www.staradvertiser.com/2022/12/28/hawaii-news/former-chef-known-for-generosity-gets-a-life-changing-gift/) and found his contact information accordingly. 

### Two Additional Sources
* [US Organ Transplants, Categorized by Racial Group and Ethnicity](https://github.com/chlodowling/J124-Final-Dowling/blob/f0c9dd738012a4b7049db495049c6a7f330a6d18/National%20Data%20-%20Transplant%20by%20Race%20%26%20Ethnicity%20-%20OPTN.pdf)
    * This dataset comes from an advanced search, of organ transplants in the US categorized by ethniciy, on [UNOS' database](https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/#).
    * This dataset provides national data on organ transplants categroized by ethicity and race and the information can be used to compare Hawaii's organ transplant data to national data. This contributes to the reporting by putting into perspective the accessibility of organ transplants in the rest of the country, in comparisson to Hawaii. 
    * The dataset has been added to the repository, visible above.
 
* [US Kidney Transplants, Categoirized by Sate](https://github.com/chlodowling/J124-Final-Dowling/blob/f0c9dd738012a4b7049db495049c6a7f330a6d18/National%20Data%20-%20Kidney%20Transplants%20by%20State%20-%20OPTN.pdf)
    * This dataset comes from an advanced search, of specifically kidney transplants in the US categorized by state, on [UNOS' database](https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/#).
    * If Milton Arellano, mentioned above, was interviewed for his story, this dataset would provide context as to how many kidney transplants occur in Hawaii versus California. This contribues to the reporting by looking at how the frequency of organ transplants vary by state. It is important to note that his additional dataset would _simply provide information on the frequency of kidney transplants, not conclusions that a patient is more likely to receive a kidney in one state over another_. Drawing that conclusion would disregard factors such as population size and the number organ ransplant sites.  
    * This dataset has been added to the repository, visible above. 

## Preparing For Data Analysis  

1. ### Source Data
    1. TODAY

2. ### Clean Data 
    1. TODAY

3. ### Ask Questions
    1. Which racial or ethnic group in Hawaii received the most transplants in 2021? Is this proportional to Hawaii’s 2021 population demographics? 
    2. From 1988 to present, has the racial or ethnic group that receives the most transplants each year in Hawaii changed over time? If so, in what year(s) was it different than the group found in question #1?
    3. Which disease has led to the most transplants in Hawaii, from 1988-present?
    4. What is the breakdown of the most common diagnosis by racial or ethnic group in Hawaii, from 1988-present, that results in requiring an organ transplant? 
    5. Is there one disease that has impacted individuals from all 8 racial or ethnic groups in Hawaii, resulting in an organ transplant? Is this in line with the United State’s most common diagnosis that results in requiring an organ transplant?

   
4. ### Define Key Assumptions
    1. TODAY

## Data Analysis 
_The following are five questions relevant to the dataset along with step-by-step answers to each of the questions:_ 

### Question 1: Which racial or ethnic group in Hawaii received the most transplants in 2021? Is this proportional to Hawaii’s 2021 population demographics? 
1. First, I looked at the "HI Transplants/Ethnicity" sheet. 
2. Then, I created a pivot table that summed up the total number of organ transplants for each racial or ethnic group in 2021. To create the pivot table I input the data from Column A (race/ethnicity) to be the data for the rows and sorted by SUM of 2021 in descending order. Next I input the values to be 2021, sumarized by SUM. To ensure I was only looking at necessary data, I filtered out both blank cells and "All ethnicities" as I only needed the individual breakdowns of each race/ethnicity.

_IMAGE 1_

* From this pivot table, it is clear that of the 64 total organ transplants that occured in Hawaii in 2021, 35 of the transplant recipients were Asian, Non-Hispanic patients. 
3. Then, to compare this to Hawaii's population demographics from 2021, I referred to the United States Sensus Bureau's 1-Year Estimate Detailed Table, derived from the 2021 American Community Survey. This table breaks down Hawaii's population demogrpahics for 2021. This data was imported into my google sheets workspace and is accessible under the "Hawaii US Census Data 2021" sheet and is also seen below. To analyze this data, I looked at row 6, "Asian alone," which that states in 2021 of the 1,441,553 people in Hawaii that year, 536,161 were Asian.

_IMAGE 2_

4. To see if the amount of organ transplants on Asian patients is proportional to Hawaii's percetage of Asians in the state in 2021, I compared the percentage of Asian transplant recipients in 2021 in Hawaii to Hawaii's percentage of Asian residents in 2021. To do this, I first found the percentage of organ transpalants on Asian patients in 2021, which is:
* (35/64)(100) = **54.68% of organ transplants in Hawaii in 2021 were on Asian patients**
 
5. Then I found the percentage of Asian residents in Hawaii in 2021, which is:
* (536,161/1,441,553)(100) = **37.19% of Asian residents in Hawaii**
 
This means that in 2021, the percentage of Asian patients who received organ transplants in Hawaii in 2021 was _**not proportional**_ to the number of Asian residents in Hawaii in 2021 as the percentage of Asian organ donations is much larger than the percentage of Asian residents in Hawaii.

### Question 2: From 1988 to present, has the racial or ethnic group that receives the most transplants each year in Hawaii changed over time? If so, in what year(s) was it different than the group found in question #1?
1. TODAY
2. qefv
3. qerg
4. qerg
5. qeg

### Question 3: Which disease has led to the most transplants in Hawaii, from 1988-present?
1. TODAY
2. qefv
3. qerg
4. qerg
5. qeg

### Question 4: What is the breakdown of the most common diagnosis by racial or ethnic group in Hawaii, from 1988-present, that results in requiring an organ transplant? 
1. TODAY
2. qefv
3. qerg
4. qerg
5. qeg

### Question 5: Is there one disease that has impacted individuals from all 8 racial or ethnic groups in Hawaii, resulting in an organ transplant? Is this in line with the United State’s most common diagnosis that results in requiring an organ transplant?
1. TODAY
2. qefv
3. qerg
4. qerg
5. qeg

## Data Visualizations 
1. Bar chart, Line chart, Scatterplot, Area chart,  Choropleth map
2. WEDNESDAY
