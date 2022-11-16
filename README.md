# Stats-in-R
Intestinal parasitic infection data cleaning and analysis in R ~ Test of asssociation
Introduction 
In this project, I analyzed the dataset on the topic “INTESTINAL PARASITIIC INFECTION AND DETERMINANT FACTORS AMONG HIV POSITIVE PATIENTS ATTENDING A LOCAL HOSPITAL” The name of the hospital hasn’t been disclosed for ethical reasons.
In this study, the researchers sought to know the:
1.	Prevalence of Intestinal Parasitic Infection among HIV positive patients attending the hospital
2.	Identify the different types of intestinal parasites infesting HIV positive patients attending the hospital
3.	Outline the determinant factors of Intestinal parasitic infections among HIV positive patients attending the hospital (Association between demographic factors and prevalence of parasites)
4.	Outline the significant risk factors and the odds of being infested by a parasite amongst the participants.


Hypothesis
Ho – There are no intestinal parasites amongst HIV patients
-	There is no significant relationship between demographic factors and presence of intestinal parasites
-	There is no significant relationship between risk factors and presence of intestinal parasites
-	The odds of getting infested by an intestinal parasites is 1.
Analysis
The data was analyzed using R statistical software version 4.2.1.
First we imported the data into R, 
Missing value analysis
Assign labels to dummy variables
Data exploration to fully understand the data
Get the Demographic characters frequencies 
Analyzed prevalence of intestinal parasites
Got the frequencies of the different parasites
I ran the crosstabs and chi square test to see the demographic factors that were significantly associated with the presence of the parasites
I ran a second crosstab and chi square test to determine any significant association between risk factors and the presence of the parasites.
Lastly, I ran a logistic regression model using all factors that were significant from the chi square test to the odds of a patient getting infestation with a parasite.

