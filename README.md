Author: Jeehye Choi [choi.jeehye@gmail.com]

Upload date: March 24, 2021

Description: Dataset analyzed for the following paper: Jeehye Choi, Takayuki Hiraoka, and Hang-Hyun Jo, Spontaneous versus interaction-driven burstiness in human dynamics: The case of Wikipedia edit history [https://arxiv.org/abs/2011.01562] 


0. The dataset we analyzed was derived from the Woo-Sik Son's preprocessed dataset of Wikipedia edit history. The original file is "enwiki-20151002-stub-meta-history.xml.gz" (278 GB when unzipped) that was uploaded on October 2, 2015 (https://dumps.wikimedia.org/enwiki/).

1. The file "article_wikiTITLE.csv" contains the article IDs and titles for the articles that were edited more than 10,000 times.

2. The file "editor_wikiID.csv" contains the editor IDs and names for the editors who edited more than 1% of edits of the articles in "article_wikiTITLE.csv".

3. The file "article_editor0.01_aucTF.csv" contains the article ID and the editor ID for each article-ego pair analyzed in our paper, and whether the AUC is defined (True) or not (False).

4. Each file "Time_series/article{\#ID}_time_user_bot.csv" contains the timestamp and the editor ID of each edit in the article. The timestamp is in Unix time. The last column has the value of "0" ("1") if the editor is human (bot). 

(???) Identity numnbers are assigned for editors in our wikipedia time series. Please do not confuse own "User ID" on the Wikipedia page information.
