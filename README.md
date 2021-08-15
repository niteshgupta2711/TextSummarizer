# TextSummarizer
1.  Create a Vocabulary using `moby.txt`
2.  Create a Word_frequency Dict and Normailize it Either by Dividing the `word_freq` by total or Max value.

# Sent_Score
1.  Sent_score or `Sentence_score` is Sum of Normalized words Within the Sentence.
2.  The Sentence here is Extracted by using `Sent_tokenizer` in `NLTK` from text.
3.  Create a sent_score dict to Store sent_scores in key value Pairs.
4.  Extract words from sentences using `word_ tokenizer` and calculate the sent_score.
5.  This sent_score dict as Passed a parameter in `nlargest function` to give a summary based on sent_score. 
