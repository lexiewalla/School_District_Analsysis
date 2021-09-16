# School_District_Analsysis

### Overview

The purpose of this project was to help Maria and the school board officials analyze the performance of all the schools on standardize testing. We were able to utilize our skills we learned for python last week and apply them this week using pandas. We were given two large data sets, information about the schools and information about the students. We combined these data sets into one large dataset and were able to pull out and piece together different bits of information to paint a better picture. In the module, we looked at the data, and told there was some fraud going on, because of this we had to exclude a portion of the data. The data that needed excluded were the 9th grade scores at Thomas High School. Once we took out the bad data, we were able to put together the rest of the data and analyze the math and reading scores and budgeting per school and grade based on the new results. 

## Results

•	The district summary is showing an overview of all the schools. It shows us the total budget of the school district, the total students, what the average math and reading grades are and the overall passing percentage. After replacing all scores for the ninth grade at Thomas High School the overall district summary was not affected much. Prior to replacing the ninth-grade scores the overall passing % for the district was 65%, when taking out the scores, the over all passing percentage dropped 0.1%.
<img width="781" alt="district_summary" src="https://user-images.githubusercontent.com/45208773/133653801-0c8dab50-f82d-4906-a342-153b8035655c.PNG">


•	The school summary is showing all the stats for each individual school. These stats were not greatly affected by the replacement of the ninth-grade grades. The passing percentages for math, reading and overall great decreased due to replacing the ninth-grade scores. The passing percentages for math and reading for Thomas High School were in the 90’s and now the averages are in the upper 60’s. There was a total of 39,170 reported grades for each subject and we replaced 461 of those grades. The first image is showing the overall grades with out the missing ninth-grade scores, the second image is showing the effect on the grades after removing the ninth grade scores.
<img width="703" alt="without missing grades" src="https://user-images.githubusercontent.com/45208773/133655349-3d0728f9-7444-4a05-bed4-28b54e4ed8a9.PNG">


<img width="724" alt="65" src="https://user-images.githubusercontent.com/45208773/133654265-0fc4bb45-11f6-4c88-9483-57ad87bbc6a8.PNG">


•	Originally, Thomas High School was in the top 5 schools for overall all passing percentage.  They were at about 90% passing rate prior to replacing those grades. Looking at the overall stats for Thomas High School, after replacing their 9th grade math and reading scores, their overall passing percent is about 65%. This is a significantly lower than what their percentage of overall passing was. Luckily this did not put them in the bottom five performing schools.
<img width="837" alt="top 5" src="https://user-images.githubusercontent.com/45208773/133654287-17f2e182-9cb0-4844-a380-4c2ed8d0249a.PNG">

<img width="809" alt="bottom" src="https://user-images.githubusercontent.com/45208773/133654299-084bc494-b9fb-4f98-b378-7708315b9886.PNG">

•	It does not appear that removing the ninth grade reading and math scores has an effect on the math and reading scores for the other grades. When we pull this data into a data frame and print it, it is showing Nan for both math and reading scores under the 9th grade column and all other grades are unaffected. 
<img width="569" alt="nan" src="https://user-images.githubusercontent.com/45208773/133653842-3cc7dcc5-2abd-493c-b660-a975a09aac50.PNG">


•	There was not a huge impact on the scores by school spending, school size and school type. There was a slight percentage decrease in the overall % passing in the $630-$644 spending group, charter type and medium group, because these are the groups Thomas High School is in and their over % passing dropped. 


Overall replacing the ninth-grade grades for Thomas High School did affect their overall pass percentage. It had a slight impact in each category of spending, school size, and school type. The other grades [10th, 11th, 12th] math and reading scores were not affected at all by any means.  
