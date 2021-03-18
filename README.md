### Informaiton ###
0. This Wikipedia dataset is originated by Woo-Sik Son who colloects and composes the dataset from "https://dumps.wikimedia.org/enwiki/".
The dataset was extracted from "enwiki-20151002-stub-meta-history.xml.gz" file (278 GB, decompress file) uploaded at 2015, October 2.
+ The number of article is 11,994,178 only for general article page.
7,015,214 articles had been merged to other article and 4,978,964 articles was in use (by 2015, Oct 2).
+ The number of editor including bots is 40,057,921 involed above articles.
Editors without own User ID, such as IP address, are considered as different editors.

1. The articles in "article_wikiTITLE.csv" had been edited larger than 10,000 times.

2. The editor in "editor_wikiID.csv" is who edited larger than 1% of edits in an article in the list.

3. "article_editor0.01.csv" shows article-ego pairs in our paper.

4. Files in "Time_series/article{\#ID}_time_user_bot.csv" is for an article's editing data.
+ The first column shows article identity number in "article_wikiTITLE.csv". The identity number refers "Page ID" on the page information profile at Wikipedia webpage.
+ The second column is the time (sec) from 1970-Jan-1 00:00:00 (KST). 
+ The third column shows editor identity number in "editor_wikiID.csv"
+ The fourth column refers to human and bot as "0" and "1", respectively.
+ Identity numnbers are assigned for editors in our wikipedia time series. Please do not confuse own "User ID" on the Wikipedia page information.
