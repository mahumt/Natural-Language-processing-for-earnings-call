# Natural-Language-processing-for-earnings-call

Earnings call are a special breed. Nomral dictionaries have been found to be insufficent for the financial world for sentiment analysis (Loughran and Mcdonald): <br>
https://www8.gsb.columbia.edu/financialstudies/sites/financialstudies/files/Loughran%20-%20March%202016%20-%20Textual%20Analysis%20in%20Finance.pdf

After these results were found, special financial dictionaies were introduced: <br>
https://sraf.nd.edu/textual-analysis/resources/#Master%20Dictionary <br>
https://www3.nd.edu/~mcdonald/Word_Lists_files/Documentation/Documentation_LoughranMcDonald_MasterDictionary.pdf <br>

Several resources were used in the course of doing this project (and its not entirely finished, if I feel that i can improve on the subject matter,
i will come back and improve/rewrite pieces of my code). <br>
To start, the sources include: <br>
<br> 
<br>
https://sraf.nd.edu/textual-analysis/resources/ <br>
http://kaichen.work/?p=399 <br>
https://github.com/cjhutto/vaderSentiment <br>
<br>
<br>
https://www.spglobal.com/marketintelligence/en/documents/sp-global-market-intelligence-nlp-primer-september-2018.pdf <br>
https://www.spglobal.com/marketintelligence/en/documents/mi-research-qr-nlp-part-ii-180912-new.pdf <br>
https://www.spglobal.com/marketintelligence/en/documents/nlp-iii-final-013020-10a.pdf <br>
https://pages.marketintelligence.spglobal.com/rs/565-BDO-100/images/SP%20Global_NLP%20Primer_Code_09%2006%2017.txt <br>
<br>
<br>
This exercise is adapted from Loughran and Mcdonald's website. The financial dictionary is downloaded from there and the code 
is a adapted from there, as well as from an S&P's white paper on NLP primer.  <br>
<br>
Improvements were done and GUI (tkniter) was used, so that a novice with little or no python experience will be able to use this a mini-program.
The code was run on various files to see whether it was outputting proper and stable results. <br>
Text, Csv, Xlsx (with only one sheet and very limited rows, due to RAM constraints), Pdf (the progams didn't works quite as well on it), Html was used. <br>

Future improvments can be done (but this will make the code lengthy, complicated and will require addtional RAM). <br>
We can include the ability to iterate over rows (in case of one grand csv or excel file containing all earnings), picking specific 
multiple quarters/year or companies in the rows, within that file.  <br>
And in case of files in folder (the main method used here), filtering files with specifc quarter/year or companies (using ticker). <br>
