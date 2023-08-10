# An Analysis of Organ Transplants in Hawaii by Racial and Ethnic Groups
### By Chloe Dowling

## Story Pitch Summary 
WEDNESDAY 

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
    * This dataset comes from an advanced search, of organ transplants in the US categorized by ethniciy, on [the Organ Procurement & Transplant Network's (OPTN) database](https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/#) .
    * This dataset provides national data on organ transplants categroized by ethicity and race and the information can be used to compare Hawaii's organ transplant data to national data. This contributes to the reporting by putting into perspective the accessibility of organ transplants in the rest of the country, in comparisson to Hawaii. 
    * The dataset has been added to the repository, visible above.
 
* [US Kidney Transplants, Categoirized by Sate](https://github.com/chlodowling/J124-Final-Dowling/blob/f0c9dd738012a4b7049db495049c6a7f330a6d18/National%20Data%20-%20Kidney%20Transplants%20by%20State%20-%20OPTN.pdf)
    * This dataset comes from an advanced search, of specifically kidney transplants in the US categorized by state, on [OPTN's database](https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/#).
    * If Milton Arellano, mentioned above, was interviewed for his story, this dataset would provide context as to how many kidney transplants occur in Hawaii versus California. This contribues to the reporting by looking at how the frequency of organ transplants vary by state. It is important to note that his additional dataset would _simply provide information on the frequency of kidney transplants, not conclusions that a patient is more likely to receive a kidney in one state over another_. Drawing that conclusion would disregard factors such as population size and the number of organ transplant sites.  
    * This dataset has been added to the repository, visible above. 

## Preparing For Data Analysis  

1. ### Source Data
    1. The first step of preparing for data analysis was to find data to analyze. In this project, I analyzed “Organ Transplants in Hawaii, Categorized by Ethnicity and Race” sourced from the United Network for Organ Sharing (UNOS). When looking for organ transplant data through UNOS, I was taken to an online database that is through the Organ Procurement and Transplant Network (OPTN). From [OPTN's database](https://optn.transplant.hrsa.gov/data/) I was able to conduct an advanced search to get a series of data tables highlighting organ tranplants in Hawaii per year, organ transplants in Hawaii per year categorized by race and ethicity, and national organ transplant data. 
    2. Once I gathered the datasets from OPTN, I copied them over to the "J124 Final: Organ Transplants Hawaii.csv" to analyze. I copied each dataset onto its own sheet, as seen in the .csv file. 

2. ### Clean Data 
    1. The second step of preparing for data analysis was to clean the data. After copying the data from OPTn to google sheets, the data did not require much refining as it was organized by OPTN. However, I did have to delete a blank column that appeared each time when copying the data over from OPTN to google sheets. I was able to refine my searches so specifically during the data sourcing process that the data cleaning process only consisted of formating the sourced data on the google sheet.  

3. ### Ask Questions
    1. Which racial or ethnic group in Hawaii received the most transplants in 2021? Is this proportional to Hawaii’s 2021 population demographics? 
    2. From 1988 to present, has the racial or ethnic group that receives the most transplants each year in Hawaii changed over time? If so, in what year(s) was it different than the group found in question #1?
    3. Which disease has led to the most transplants in Hawaii, from 1988-present?
    4. What is the breakdown of the most common diagnosis by racial or ethnic group in Hawaii, from 1988-present, that results in requiring an organ transplant? 
    5. Is there one disease that has impacted individuals from all 8 racial or ethnic groups in Hawaii, resulting in an organ transplant? Is this in line with the United State’s most common diagnosis that results in requiring an organ transplant?
  
*The third step of preparing for data analysis was to develop questions, as seen above, that would guide the data analysis process. The five questions above will be used as the structure for the "Data Analysis" process documented below.*

   
4. ### Define Key Assumptions

The final step before starting data analysis was to establish key assumptions that would remain true for the entirety of the data analysis process. The key assumptions go as follows:

* All questions were answered using the data set "J124 Final: Organ Transplants Hawaii.csv" mentioned above.
* For the purpose of this study, organ transplant refers to all types of organ transplants as this study does _not_ categorize the organ transplant data into organ transplant type such as liver, heart, or lung transplant. 
* For all five questions, the datasets referenced come from OTPN and one dataset comes from the US Census. 

## Data Analysis 
_The following are the five questions provided above, each relating to the story pitch. Each question is accompanied by the step-by-step process it took to reach the data findings._ 

### Question 1: Which racial or ethnic group in Hawaii received the most transplants in 2021? Is this proportional to Hawaii’s 2021 population demographics? 
1. First, I looked at the "HI Transplants/Ethnicity" sheet. 
2. Then, I created a pivot table that summed up the total number of organ transplants for each racial or ethnic group in 2021. To create the pivot table I input the data from Column A (race/ethnicity) to be the data for the rows and sorted by SUM of 2021 in descending order. Next I input the values to be 2021, sumarized by SUM. To ensure I was only looking at necessary data, I filtered out both blank cells and "All ethnicities" as I only needed the individual breakdowns of each race/ethnicity.

![Q1_Image 1](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q1_Image1.png)

From this pivot table, it is clear that of the 64 total organ transplants that occured in Hawaii in 2021, **35 of the transplant recipients were Asian, Non-Hispanic patients, making this the racial group that received the most transplants in 2021.** 

3. Then, to compare this to Hawaii's population demographics from 2021, I referred to the United States Sensus Bureau's 1-Year Estimate Detailed Table, derived from the 2021 American Community Survey. This table breaks down Hawaii's population demogrpahics for 2021. This data was imported into my google sheets workspace and is accessible under the "Hawaii US Census Data 2021" sheet and is also seen below. To analyze this data, I looked at row 6, "Asian alone," which that states in 2021 of the 1,441,553 people in Hawaii that year, 536,161 were Asian.

![Q1_Image 2](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q1_Image2.png)

4. To see if the amount of organ transplants on Asian patients is proportional to Hawaii's percetage of Asians in the state in 2021, I compared the percentage of Asian transplant recipients in 2021 in Hawaii to Hawaii's percentage of Asian residents in 2021. To do this, I first found the percentage of organ transpalants on Asian patients in 2021, which is:
* (35/64)(100) = **54.68% of organ transplants in Hawaii in 2021 were on Asian patients**
 
5. Then I found the percentage of Asian residents in Hawaii in 2021, which is:
* (536,161/1,441,553)(100) = **37.19% of Asian residents in Hawaii**
 
This means that in 2021, **the percentage of Asian patients who received organ transplants in Hawaii in 2021 was _not proportional_ to the number of Asian residents in Hawaii in 2021** as the percentage of Asian organ donations is much larger than the percentage of Asian residents in Hawaii.

### Question 2: From 1988 to present, has the racial or ethnic group that receives the most transplants each year in Hawaii changed over time? If so, in what year(s) was it different than the group found in question #1?
1. First, I created a pivot table, selecting "Race/Ethnicity" as the rows, sorting by "Race/Ethnicity" in ascending order. 
2. Next, I added a filter to not include "All Ethnicities" and any blanks in the pivot table, as I need to see the number of organ transplants each racial and ethnic group received each year. 
3. After this, I then input each year from 1988 to present as the values, shown as columns and sumarized by MAX.
4. I then froze column 1 so I could always see the racial or ethnic group.
5. I got this pivot table:

![Q2_Image 1](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q2_Image%201.png)
![Q2_Image 2](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q2_Image%202.png)
![Q2_Image 3](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q2_Image%203.png)
![Q2_Image 4](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q2_Image%204.png)

6. I then compared each year's grand total, which displays the number of transplants from the racial or ethnic group with the most amount of transplants, to the number of "Asian, Non-Hispanic" transplants that occured the same year. As  "Asian, Non-Hispanic" is the racial group that received the most transplants in 2021, found in question 1, I simply looked at this group in comparisson to the total to see if the numbers were the same in both cells.
7. After doing this, I was able to determine that the racial or ethnic group that has received he most transplants each year has stayed consistent for all but one year. In 1991, as seen in column E, the grand total did not match with the "Asian, Non-Hispanic" row. Thus the racial group that recevied the most amounnt of transplants in 1991 was "Pacific Islander, Non-Hispanic." In 1991, 13 Pacific Islander patients had an organ transplant, in Hawaii, in comparisson to the 11 Asian paients who had an organ transplant. From 1988 until the present, except for 1991, the racial group that recevied the most amounnt of transplants was "Asian, Non-Hispanic."

![Q2_Image 5](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q2_Image%205.png)

As such, the data analysis for question 2 reveals that over time, Asian patients have received the most organ transplants each year in Hawaii, except in 1991 when 13 Pacific Islander patients had organ transplants and 10 Asian paients had organ transplants. Thus, the racial group that receives the most transplants each year in Hawaii _**has stayed consistent with Asian patients receiving the most in all but one year in 1991.**_

### Question 3: Since 1988, which diagnosis has led to the most organ transplants in Hawaii?
1. First, I selected the data from B1 to C21 on the "HI Transplant/Ethnicity/Diagnosis" sheet as I only needed the diagnosis names (Column B) and total number of organ transplants in Hawaii since 1988 (Column C) in order to answer this question. 
2. I then copied the selected data over to a new sheet titled "Diagnosis --> Most Transplants" visable on "J124 Final: Organ Transplants Hawaii.csv."
3. After pasting the data, I deleted row 2 which contained the total number of organ transplants that have occured since 1988. I did this as I needed the individual organ transplant breakdowns as a result of each diagnosis, not all of the diagnoses combined. 
4. I then selected colomn B and sorted the sheet from Z->A.

![Q3_Image1](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q3_Image1.png)

From this dataset above, it is apparent that since 1988, _**Glomerular Disease is the diagnosis that has led to the most organ transplants in Hawaii, causing 544 transplants.**_ Diabetes is the second most disase causing organ transplants. Non-Cholestatic Cirrhosis is the third most disease casuing organ transplants. 

### Question 4: Since 1988, what has been the most common diagnosis, that results in an organ transplant, for each racial or ethnic group in Hawaii? 
1. I created a pivot table, seen on the "PT: Most Common Diagnosis by Race" sheet, in order to answer this question. To create the table, I used the data on the "HI Transplant/Ethnicity/Diagnosis" sheet. 
2. For the rows of the pivot table, I input "Race/Ethnicity" and "Diagnosis," both sorted by "MAX of To Date" in descending order.
3. For the vlaues, I input "To Date" as this column represents the total number of organ transplants in Hawaii since 1988 until 2023. The "To Date" values are summarized by "MAX."
4. I then applied two filters to this pivot table, the first being to "Diagnosis" where I deselected "any blanks" and "All Diagnoses" as I needed the individual organ transplant breakdowns as a result of each diagnosis, not all of the diagnoses combined. The second filter was applied to "Race/Ethnicity" where I deselected "All Ethnicities" as I needed to look at the individual race/ethnicity breakdowns, not all of the races/etthnicties combined.
5. I was then able to analyze this pivot table:

![Q4_Image 1](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q4_Image1.png)
![Q4_Image 2](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q4_Image2.png)
![Q4_Image 3](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q4_Image3.png)
![Q4_Image 4](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q4_Image4.png)

By looking at the pivot table, it is apparent that since 1988 the most common diagnosis, that results in an organ transplant, for each racial or ethnic group in Hawaii is:
* **Asian, Non-Hispanic: Glomerular Disease** causing 323 organ transplants
* **Pacific Islander, Non-Hispanic: Glomerular Disease** causing 127 organ transplants
* **White, Non-Hispanic: Non-Cholestatic Cirrhosis** causing 84 organ transplants
* **Multiracial, Non-Hispanic: Diabetes** causing 58 organ transplants
* **Hispanic/Latino: Glomerular Disease** causing 21 organ transplants
* **Black: Glomerular Disease** causing 6 organ transplants
* **American Indian/Alaska Native, Non-Hispanic: Glomerular Disease** causing 1 organ transplant

### Question 5: Is there one diagnosis that has impacted individuals from all seven listed racial and ethnic groups in Hawaii, resulting in an organ transplant? If so, is this in line with the United State’s most common diagnosis that results in requiring an organ transplant?
1. To answer this question, I first referred to the "PT: Most Common Diagnosis by Race" pivot table I created in question 4. This pivot table has information on the diagnoses that have required patients in Hawaii to have organ transplants, categorized by racial and ethnic group. When analyzing this data, it was apparent that since 1988 there has only been one "American Indian/Alaska Native, Non-Hispanic" organ transplant patient in the state of Hawaii. From the pivot table, it is evident that Non-Cholestatic Cirrhosis is the diagnosis that resulted in the "American Indian/Alaska Native, Non-Hispanic" patients need for an organ transplant.
2. After discovering this, I needed to confirm that there were patients diagnosed wih Non-Cholestatic Cirrhosis from the other six racial and ethnic groups as well. As such, I referrred back to the data on the "HI Transplant/Ethnicity/Diagnosis" sheet to make a pivot table, visibile on the "PT: One Diagnosis, All Groups" sheet. With this pivot table, I needed to reveal how many times the Non-Cholestatic Cirrhosis diagnosis was mentioned on the dataset by using COUNTUNIQUE. 
3. As such, for the first step of creating the pivot table I input "Diagnosis" as the rows, sorted by diagnosis in ascending order.
4. I then input "Race/Ethnicity" as the rows as well, sorted by race/ethnicity in ascending order.
5. Then, for the values, I input "Diagnosis" summarized by "COUNTA."
6. I then applied two filters to this pivot table, the first being to "Diagnosis" where I deselected everrything but Non-Cholestatic Cirrhosis. The second filter was applied to "Race/Ethnicity" where I deselected "All Ethnicities" as I needed to look at the individual race/ethnicity breakdowns, not all of the races/etthnicties combined.
8. I was then able to analyze this pivot table:

![Q5_Image 1](https://github.com/chlodowling/J124-Final-Dowling/blob/b3c6a69b3a02b43a85a20ee4fc87b4c6ea5458cd/J124-Screenshots/Q5_Image%201.png)

From this pivot table, it is clear that **Non-Cholestatic Cirrhosis is the one diagnosis that has impacted individuals from all seven listed racial and ethnic groups in Hawaii, resulting in an organ transplant** as this diagnosis is infact mentioned 7 times on the "HI Transplant/Ethnicity/Diagnosis" datasheet.  

7. Theh, to see if Non-Cholestatic Cirrhosis is this in line with the United State’s most common diagnosis that results in requiring an organ transplant, I conducteed an advanced search on the OPTN database to get national organ transplant data from 1988 to present categorizeed by race/ethnicity.
8. Once I accessed the data from [OPTN's database](https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/#) I then copied the dataset over to the .csv file listed above on a new sheet titled "US Transplants/Ethnicity/Diagnosis."
9. Then I seelected Column C (national amount of organ transplants to date from 1988) and sorted sheet from "Z -> A."
10. I then got this table (the table extends beyond column L, however the only columns we're looking at are columns B and C):

![Q5_Image 2](https://github.com/chlodowling/J124-Final-Dowling/blob/994a6e1fd22273b9552c6467243d2d89708497b9/J124-Screenshots/Q5_Image%202.png)

11. From here I was able to see the leading diagnoses resulting in the need of an organ transplant, nationally.

As such, it is clear that **Non-Cholestatic Cirrhosis is not in line with the United State’s most common diagnosis** that results in requiring an organ transplant as **the most common diagnosis that results in an organ transplant is Diabetes, which has caused the need for 159,114 organ transplants in the US since 1988 until the present.** Glomerular Disease is the second most leading diagnosis that results in an organ transplant, having resulted in 130,421 organ transplants in the US since 1988 until the present. Non-Cholestatic Cirrhosis however is the third most leading diagnosis that results in an organ transplant, having resulted in 116,282 organ transplants in the US since 1988 until the present.

## Data Visualization 
1. Bar chart
