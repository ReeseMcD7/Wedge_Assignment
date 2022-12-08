
# Applied Data Analytics

## Wedge Project



### Task 1

* Files for this task: 

Wedge_Data_Eng_Task1.ipynb:

This notebook unzips, formats, and cleans the Wedge transaction data files and then uploads them to Google BigQuery.

### Task 2

* Files for this task: 

Wedge_Data_Eng_Task2.ipynb:

This notebook uses the cleaned and uploaded data to generate a sample of owners and their transactions and writes it to csv within the main directory.

### Task 3

* Files for this task: 

Wedge_Data_Eng_Task3.ipynb:

This notebook queries the uploaded data to gather a collection of summary tables and uses them to build a db. database file. 


## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - john_results)/john_results)`. 



|  Query  |  Your Results  |  John's Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |86032709|85760139|272570|0.32%|
| January 2012 Rows  |1070907|1070907|0|0%|
| October 2012 Rows  |1042287|1042287|0|0%|
| Month with Fewest  |December|February| Yes  | NA  |
| Num Rows in Month with Fewest  |4865009|6556770|-1691761|-25.80%|
| Month with Most  |May|May| No  | NA  |
| Num Rows in Month with Most  |6639603|7578372|-938769|-12.39%|
| Null_TS  |72459129|7123792|65335337|917.14%|
| Null_DT  |0|0|0|0|
| Null_Local  |227538|234843|-7305|-3.11%|
| Null_CN  |0|0|0|0|
| Num 5 on High Volume Cards  |14987|14987| No  | NA  |
|  Num Rows for Number 5 |464469|460630|3839|0.83%|
| Num Rows for 18736  |12317|12153|164|1.35%|
| Product with Most Rows  |banana organic|banana organic| No  | NA  |
| Num Rows for that Product  |915315|908639|6676|0.73%|
| Product with Fourth-Most Rows  |avocado hass organic|avocado hass organic| No  | NA  |
| Num Rows for that Product  |449060|456771|-7711|-1.69%|
| Num Single Record Products  |2259|2769|-510|-18.42%|
| Year with Highest Portion of Owner Rows  |2014|2014| No  | NA |
| Fraction of Rows from Owners in that Year  |0.7591|0.7591|0|0|
| Year with Lowest Portion of Owner Rows  |2011|2011| No  | NA |
| Fraction of Rows from Owners in that Year  |0.7372|0.7372|0|0|

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project --> 
What a puzzle this project was. Getting through the code was an adventure, but the satisfaction of finally building all this python code that works exactly as intended (said with the realization that you and I came up with different numbers) was a uniquely satisfying moment (especially with no prior experience with the language). This project made me confident that my personality is well configured for this kind of work. Though you admit it a bit chaotic, I find this course structure preferable to a standard college course. I was engaged with the work instead of hacking my way to the deadline of each project. It was only near the end when I felt like I knew what was happening in the material, but here I’m basking a little the tail of a eureka moment. I felt like I just went through something that resembles real work and now can confidently approach new coding problems. The hang-ups and snags felt similar to the ones I encounter in music, art, language, and trading. I learned that the tougher hurtles need to be addressed with more discerning focus. I’m a little sad that it’s over to be honest. Thanks for the challenge!
