# Rossetti-corpus
Word frequency is an important textual feature that enables thematic analysis in discourse linguistics. It can help researchers establish recurring topics in an individual's speech, oral or written, that have special significance. Its applications include the analysis of an author's literary style or an individual's speech patterns or even state of mind. There is a variety of fields where such knowledge may be useful, from AI speech generation to clinical psychology.

This sample project focuses on part-of-speech tagging of Christina Rossetti's poems to determine most frequently used nouns, verbs, adjectives and adverbs that contribute to the thematic richness of the author's texts.

# The project includes the following steps:

1. Web scraping the poem data from gutenberg.org using BeautifulSoup
2. Cleaning the text to remove special symbols, webpage introduction and disclaimer
3. Removing punctuation, lowercasing, tokenizing and lemmatizing the text
4. Removing stopwords and part-of-speech tagging with NLTK and Stanza
5. Visualizing the resulting 50 most common terms and parts of speech

# Findings:

There is no doubt that Stanza's pos-tagging capabilities are far more advanced when compared to NLTK and Spacy. The tagged corpus produced by using the former can be successfully integrated into any text-generative models, including chatbots. However, as expected from any advanced model, its use is more cost-intensive and time-consuming.

From the linguistic perspective, after analyzing common words in Rossetti's poetry, it becomes evident that the most pronounced themes in the poems include love, life and death, body allusions, nature and time (especially the change of seasons).
