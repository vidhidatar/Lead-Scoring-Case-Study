Lead Scoring Case Study

Contributors: 
Vidhi Surana
Shubham

Batch : DS C48

File Names:

1.Python commented file: Lead_Scoring_Case_Study_final.ipynb
2.Word File of Subjective Questions: Assignment_Subjective Questions_Answers.docx
3.Presentation : Lead_Scoring_Case_Study_PPT.pdf
4. Summary Report : Summary_Report.pdf
5. README.md : Documentation of the case study in short and file details
/*************************************************************************************************************************/
Problem Statement
Main Problem to be solved is to improve the Lead Conversion Rate of the education company called X Education that sells online courses to industry professionals
On any given day, many professionals who are interested in the courses land on their website and browse for courses.
 The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead or a potential customer. Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted.

 Lead Conversion Rate  -> Out of total number of leads, how many convert into potential customers.

***************************************************************************************************************************/
What is our job?

1. X Education has appointed you to help them select the most promising leads(hot leads), i.e. the leads that are most likely to convert into paying customers.
2. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

******************************************************************************************************************************/
Data provided

-- You have been provided with a leads dataset from the past with around 9000 data points.
-- This dataset consists of various attributes such as lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not.
-- The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.

******************************************************************************************************************************/

Approach Used


1. The Machine Learning algorithm will work at the level between the Initial Pool of Leads and Leads Nurturing.
2. The filter of ML Model provides the Binary Classification Model predicting which leads have high chances of converting into lead(1 or 0)
3. Rather than passing all the potential customers to the sales team, only the ones that are filtered are passed.
4. With the help of Ml, LCR will increase and Sales team will not reach out to people having lesser chances of Converting into a lead.

Goal : Build a Logistic Regression Model which will assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. Target lead conversion rate to be around 80%.

********************************************************************************************************************************/


