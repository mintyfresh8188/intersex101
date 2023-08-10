##More common and more normal than you think!##

One of the numbers commonly cited regarding the occurrence of DSDs/intersex conditions is 1.7%, but this is an estimate and it is frequently debated. Some researchers argue that it’s much rarer, occurring at a rate of 1 out of 10K, and have defined DSD as only those with ambiguous genitalia. These are some huge differences in estimation, and it does not help that over 70% of those with a DSD do not receive a specific or accurate diagnosis. Therefore, we will take to a random population sample who have submitted their human genome data to look for incidence of likely DSDs, even if they were not reported as a DSD. A difference of sex development, as mentioned previously, is described as a congenital and significant difference to the chromosomes, gonads, internal reproductive organs, genitalia and sex hormone profile. 

Please see the following data sets (Metabolic/endocrine, Genitourinary, Congenital Anomalies) for the raw data and tables made for analysis. 

Some questions answered by this data analysis will be:

What is the total amount of unique respondents across the three data sets?
1. Import CSV file into Google Sheets
2. Copy Column A of all sheets into a new spreadsheet into Column A of the new sheet
3. Create pivot table 
4. Values: Count unique

Return: 2318 unique participants 

How many people had a condition not otherwise listed compared to the number of people who had any diagnosis in each data set? 

1. Sort Data Range (advanced)
2. First sort by Column D
3. Then sort by Column E
4. This should return total number of respondents with diagnoses
5. Copy sorted data into a second sheet — include only the diagnoses
6. However there are respondents who write “no”, this can be addressed
7. Delete all the cells that say no/none/n/a after Column D starts giving blanks and then delete the rows
8. Do this for the other two data sets

Endocrine/metabolic/nutritional/disease survey Total: 1243
Congenital Traits and Anomalies Survey Total: 314
Genitourinary disease/anomalies Survey Total: 1133

1. In the copied sheet, insert row and create a header row 
2. Label column A diagnosis and column B not listed
3. Select all, create a filter
4. Filter out blanks
5. Copy filtered column B and paste into third sheet, which will give the value of all conditions not listed
6. Do this for all sheets

Other conditions Not Listed: 
Endocrine/metabolic/nutritional/disease survey: 179
Congenital Traits and Anomalies Survey: 143
Genitourinary disease/anomalies Survey: 157

How many people in the survey have a likely DSD? 

It doesn’t seem like there is an option listed for DSDs in the second column where participants select from a list of conditions. This means it is likely to be in Other Conditions Not Listed. 

1. Create filter view
2. Sort “Other Conditions Not Listed” (Column C) by Condition 
3. Deselect Blanks
4. Do this for each sheet
5. From this point onwards, specialty knowledge regarding DSDs is required. I have co authored studies on DSDs and facilitate research and support groups for people with DSDs. Therefore, I have extensive knowledge about differences of sex development. I have shared my understanding of DSDs on another page in this repository, and you may read more about it here. 
6. Isolate conditions that fit the criteria of DSD (congenital significant difference to the sex characteristics)
7. Highlight each relevant condition across all three sheets
8. Exit filter view for each sheet 
9. Create new filter view
10. Filter column C by colour

Now, let’s double check that there aren’t any duplications 

1. Copy the highlighted results over to a new sheet from each data set (Sheet1)
2. Create Sheet2
3. Copy Column A (patient reference numbers) to Sheet2
4. In cell B1, write a VLOOKUP formula
5. =VLOOKUP(A1,Sheet1!$A$2:$E$15,5,FALSE)
6. Drag the cell all the way down to the end of the values in Column A
7. Create new filter view
8. Filter out blanks 
9. Go to Data
10. Cleanup -> remove duplicates
11. Select column A
12. One of the references was duplicated, so the extra was removed

There are a total of 9 references who have a condition that fits clinical definition of DSD

What is the incidence of reproductive disorders/anomalies compared to general endocrine disorders? 

1. Go to sheet with just the diagnosis and not listed categories
2. Make a pivot table 
3. Filter by diagnosis first 
4. Select all reproductive disorders, deselect non reproductive disorders
5. Obtain CountA value
6. Make second pivot table 
7. Filter by not listed
8. Select all reproductive disorders
9. Obtain CountA value
10. Filter by diagnosis now 
11. Obtain CountA of the overlap
12. Add the first and second CountA, then subtract the third

115+32-5 = 143

Incidence of reproductive disorders in the Endocrine sample is 143

What is the incidence of reproductive disorders in the entire sample size?

1. Create a filter for the entire sheet and a new filter view
2. Filter by diagnosis for reproductive disorders
3. Copy and paste results onto a new sheet: SheetRepro
4. Exit filter view, and then filter again by conditions not listed for reproductive disorders
5. Copy and paste results onto SheetRepro under the previous paste
6. Remove the header row if it was pasted
7. Repeat process for the other two data sets, pasting under the previous filtered data in SheetRepro
8. Once all the data is in SheetRepro, insert a pivot table 
9. Add value for Participant 
10. CountUnique 

Incidence of reproductive disorders in the entire sample size is 620
