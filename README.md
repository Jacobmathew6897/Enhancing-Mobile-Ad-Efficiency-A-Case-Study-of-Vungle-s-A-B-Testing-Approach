# Enhancing-Mobile-Ad-Efficiency-A-Case-Study-of-Vungle-s-A-B-Testing-Approach

Introduction

The relationship between inflation and crime rates is a complex and multifaceted issue that has been the subject of much research. 
While some studies have found a positive correlation between inflation and crime, others have found no significant relationship or even a negative relationship. 
The effects of inflation on crime rates are likely to vary depending on several factors, including the specific type of crime, the local economy, relevant policies and statutes, demographic factors such as age distribution and migration patterns, as well as many other factors.  As such it is difficult to untangle the complex web of relationships that exist between all these variables.
The present study aims to study the relationship between crime and inflation in the city of Dallas.  
Although inflation is constantly on the rise, the United States experienced a higher rate of inflation in the last couple of years.
The effects of rising food and gas prices were well documented in the media which drew attention to the hard times many Americans endured (wcctv 2023). 
If there is a relationship between inflation and crime, the recent high level of inflations makes this the perfect opportunity to study its effects on crime.
Additionally, this study also aims to study if inflation has an effect on specific types of crimes such as theft, burglary and robbery as these might be a more common response to scarcity than other types of crimes such as homicide. 
It is important to note that no such study has been conducted in Dallas in recent years, so the present study adds significantly to the cannon of knowledge in this field. 
Finally, the importance and significance of this research lies in its potential to contribute valuable insights that can inform policy decisions related to crime prevention, community development, and social welfare policies during difficult economic times.

Dataset:
Vungle Case Study
Content of the dataset:
Strategy: The version of the ad-serving algorithm used (e.g., Vungle A or Vungle B). Date: The date on which the data was collected.
Impressions: The number of times ads were shown to users.
Completes: The number of times an ad was watched to completion.
Clicks: The number of times users clicked on ads.
Installs: The number of times users installed the app after viewing the ad. eRPM: Effective revenue per thousand impressions.

Project Description:
Wayne Chan, Chief Technology Officer of Vungle planned to test the new algorithm in parallel with the existing current algorithm. As was typical in such experiments, the two conditions, A (Vungle’s existing algorithm) and B (the data science approach) would be evaluated in parallel on randomly assigned users. Since, new algorithm was unproven, Chan’s team thought that it would make sense to direct only 1/16th of the users to the B condition.
The other randomly assigned 15/16th of users would receive an ad based on the existing algorithm (i.e., A condition). Users were assigned to A or B using MD5 hashing process. An MD5 hash transforms each user ID into a unique 32-character hexadecimal string. Each character of the hexadecimal string could be 0-9, A, B, C, D, E, F. Each character would occur with equal likelihood, making it simple for Vungle to direct traffic in 1/16th increments using a logic statement.
Will analyze the results of Vungle’s A/B testing to determine the impact on ad efficiency. Will use statistical analysis to compare the performance of the two algorithms.
