#   Test of Association and Logistic regression-in-R <br>
Intestinal parasitic infection data cleaning and analysis in R ~ Test of asssociation <br>
Introduction <br>
In this project, I analyzed the dataset on the topic “INTESTINAL PARASITIIC INFECTION AND DETERMINANT FACTORS AMONG HIV POSITIVE PATIENTS ATTENDING A LOCAL HOSPITAL” The name of the hospital hasn’t been disclosed for ethical reasons.<br>
In this study, the researchers sought to know the:<br>
1.	Prevalence of Intestinal Parasitic Infection among HIV positive patients attending the hospital<br>
2.	Identify the different types of intestinal parasites infesting HIV positive patients attending the hospital<br>
3.	Outline the determinant factors of Intestinal parasitic infections among HIV positive patients attending the hospital (Association between demographic factors and prevalence of parasites)<br>
4.	Outline the significant risk factors and the odds of being infested by a parasite amongst the participants.<br>


Hypothesis<br>
Ho – There are no intestinal parasites amongst HIV patients<br>
-	There is no significant relationship between demographic factors and presence of intestinal parasites<br>
-	There is no significant relationship between risk factors and presence of intestinal parasites<br>
-	The odds of getting infested by an intestinal parasites is 1.<br>
Analysis<br>
The data was analyzed using R statistical software version 4.2.1.<br>
First we imported the data into R, <br>
Missing value analysis<br>
Assign labels to dummy variables<br>
Data exploration to fully understand the data<br>
Get the Demographic characters frequencies <br>
Analyzed prevalence of intestinal parasites<br>
Got the frequencies of the different parasites<br>
I ran the crosstabs and chi square test to see the demographic factors that were significantly associated with the presence of the parasites<br>
I ran a second crosstab and chi square test to determine any significant association between risk factors and the presence of the parasites.<br>
Lastly, I ran a logistic regression model using all factors that were significant from the chi square test to the odds of a patient getting infestation with a parasite.<br>

