# comp_lit

This repository is a sandbox for the final project of Computational Literacy course (LDA-H305) given by [Eetu Mäkelä](https://jiemakel.gitbook.io/cl4hss) in 2022 (autumn term, period 2). 

1. Background and research question
The research question is **How does the Hong Kong-based electronic newspaper Southern China Morning Post (SCMP) present climate change issues?** 
This is an investigation on digital environmentalism in Asia, with aims of implementing text analysis tools/methods to explore discourses of climate change in electronic news. More specifically, I aim to identify common themes and frames of climate change using a novel sample, with inspirations from Hase et al. (2021), Climate change in news media across the globe: An automated analysis of issue attention and themes in climate change coverage in 10 countries (2006–2018) and Broadbent et al. (2016), Conflicting climate change frames in a global field of media discourse. The analysis sheds light on climate change discourses in Hong Kong (SCMP), which has been overlooked by existing cross-country studies of climate change journalism.

2. Data 
Online news articles of the outlet with the keyword “climate change” from 1/1/15-31/12/17 obtained from Nexis Uni with engine search. During the selected timeframe, several important international events occurred: the Paris Agreement (2015) came into force on 4th November 2016, which was followed by the presidency of Donald Trump and withdrawal of the US from the accord (June - September 2017).

The collected dataset contains 255 entries (in separate text files) with metadata (published date, word count, and several topic/industry/geography labels) and articles' contents (title and body text). To preprocess the data for analysis, three procedures were carried out.

- Extracting metadata and content from individual entry files
- Lematizing words in articles' title and body text
- Constructing a concept network of labels and articles and another of only labels

3. Analysis
The analysis was done in an explorative way, with three aspects to consider: the volumn of media coverage, the content (word level and higher level topics), and fluctuation over time of these two features.(...)


5. What does the analysis show, how does it answer the humanities/social science research question? How do the results relate to possible prior and related work?
TBA

5.Critically analyse your data and pipeline for potential bias and problems. What would still need to be done for the analysis to be trustable?
- Unable to open and distribute the dataset​ due to license restrictions
- Data representativeness is unguaranteed as I do not own access to the complete archive for data collection
- Distant reading can be restricted to understanding the material compared to close reading
- Reliance on pre-built computational without substantial fine-tuning can lead to bias
