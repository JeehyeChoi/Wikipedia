Author: Jeehye Choi (choi.jeehye@gmail.com)

Upload date: March 24, 2021

Description: Dataset analyzed for the following paper: Jeehye Choi, Takayuki Hiraoka, and Hang-Hyun Jo, Spontaneous versus interaction-driven burstiness in human dynamics: The case of Wikipedia edit history (https://arxiv.org/abs/2011.01562)


0. The dataset we analyzed was derived from the Woo-Sik Son's preprocessed dataset of Wikipedia edit history. The original file is "enwiki-20151002-stub-meta-history.xml.gz" (278 GB when unzipped) that was uploaded on October 2, 2015 (https://dumps.wikimedia.org/enwiki/).

1. The file "article_list.csv" contains the page IDs and titles for the articles that were edited more than 10,000 times.

2. The file "editor_list.csv" contains the user indexes (assigned by us, also the same as "editor ID" in the paper) and names for the editors who edited more than 1% of edits of the articles in "article_list.csv".

3. The file "article_ego_pair_list.csv" contains the page ID and the user index for each article-ego pair analyzed in our paper, and whether the AUC can be determined (True) or not (False) for each article-ego pair.

4. Each file "time_series_article{\#ID}.csv" in the compressed files "Time_series1.tar.gz", "Time_series2.tar.gz", and "Time_series3.tar.gz" contains the timestamp and the user index of each edit in the article. The timestamp is in Unix time. The last column has the value of "0" ("1") if the user is human (bot).
