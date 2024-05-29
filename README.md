
# Topic Modelling

In this study, data collected from Factiva, a large Global News database, in 2017, containing articles from the Wall Street Journal and the New York Times, was analyzed. The articles underwent preprocessing, including tokenization and stop word removal.

Topic modeling using the Latent Dirichlet Allocation (LDA) algorithm was employed to extract topics from the corpus. The coherence score was utilized to determine the optimal number of topics, with the best coherence score achieved with four topics at 0.3328. However, coherence scores for the number of topics between 2 and 10 were very close, with no clear optimal number emerging.

The coherence score plot demonstrated the distribution of coherence scores across different numbers of topics. Word clouds were generated for each topic using the word frequency dictionary, offering insights into the main themes of each topic.

Based on the coherence score, the best model was selected with four topics. The identified topics and their corresponding themes were as follows:

Topic 1: Politics, featuring words like Trump, President, and American.
Topic 2: Terrorism, highlighting words like Terrorism, attacks, and group.
Topic 3: Military and conflicts, with words such as Syria, militants, and forces.
Topic 4: Politics and military, echoing words like Trump, President, and military.
This analysis underscores the value of topic modeling in understanding how terrorist organizations are portrayed in traditional media outlets. The study revealed a predominant focus on American politics and foreign policy, with articles related to the Islamic State and its activities. Additionally, ten dominant topics related to the Islamic State, terrorism, and foreign policy were identified in the corpus.

Future studies could further leverage similar methods to gain deeper insights into how terrorist organizations are depicted in traditional media outlets, contributing to a better understanding of the dynamics between media portrayal and public perception.
