# comp_lit

This repository is a sandbox for the final project of Computational Literacy course (LDA-H305) given by [Eetu Mäkelä](https://jiemakel.gitbook.io/cl4hss) in 2022 (autumn term, period 2). 

1. Background and research question
   
The research question is **How does the Hong Kong-based electronic newspaper Southern China Morning Post (SCMP) present climate change issues?** 
This is an investigation on digital environmentalism in Asia, with aims of implementing text analysis tools/methods to explore discourses of climate change in electronic news. More specifically, I aim to identify common themes and frames of climate change using a novel sample, with inspirations from Hase et al. (2021), Climate change in news media across the globe: An automated analysis of issue attention and themes in climate change coverage in 10 countries (2006–2018) and Broadbent et al. (2016), Conflicting climate change frames in a global field of media discourse. The analysis sheds light on climate change discourses in Hong Kong (SCMP), which existing cross-country studies of climate change journalism have overlooked.

2. Data
   
Online news articles of the outlet with the keyword “climate change” from 01/09/2016-31/12/2017 obtained from Nexis Uni with engine search. During the selected timeframe, several important international events occurred: the Paris Agreement (2015) came into force on 4th November 2016, which was followed by the presidency of Donald Trump and withdrawal of the US from the accord (June - September 2017).

The collected dataset contains 255 entries (in separate text files) with metadata (published date, word count, and several topic/industry/geography labels) and articles' contents (title and body text). To preprocess the data for analysis, three procedures were carried out.

- Extracting metadata and content from individual entry files
- Lematizing words in articles' title and body text
- Constructing a concept network of labels and articles and another of only labels

3. Analysis
   
The analysis was done exploratively, with three aspects to consider: the volume of media coverage, the content (word-level and topic-level), and the fluctuation over time of these two features. Though they are intertwined in the analysis, it is divided into two parts, one focusing on media volume is available at (link) and another part on quantitative content analysis can be found at (link) (both include the source code and visualized results).

More specifically, for media volume, length per article records 764.03 words on average and 643.0 words on median. The shortest article has 167 words about "Typhoon warning as Hong Kong Observatory issues No 1 signal", published on 2017-07-22 (YYYY-MM-DD). The longest article has 3522 words about "Former top US envoy to China Gary Locke on Trump, trade and strategic mistrust", published on 2016-11-17. About half of articles have moderate length of 500-1000 words (122 entries). 

The top longest articles (18 outliers) are generally between 1500-2000 words, with only 3 exceptions (one yearly compilation article, one on US-China relations before the US Presidential Election 2016, and one after Xi Jinping's speech at the Chinese Comunist Party 19th Congress). Six of them appears to mainly feature environmental issues, ranging from biodiversity, environmental impact, air pollution, wildlife trade, electric bus, green economy. The outlier entries are concentrated around end/beginning of quarters, except for Nov 2016.

Overall, the number of words/articles published gradually accumulated without any major disruption though there exist slightly fluctuations on week-level, indicating a stable trend of the outlet itself but mild peak moments such as Nov 2016 (the US Presidential Election 2016) and  June 2017 (US withdrawal from the Paris Agreement). Two dates with most articles published are 2017-06-02 (6 entries) and 2016-11-13 (4 entries).

Quantitative content analysis includes several sumarization of the lematized words and provided topics, 

4. What does the analysis show, how does it answer the humanities/social science research question? How do the results relate to possible prior and related work

Analysis of media volume indicates that certain coverage of SCMP is reserved for environmental/climate issue regularly though it is unknown from the data how important role such reserved area plays in the entire SCMP content. International events can be opportunities for more climate change content to be featured as side issues, though they are unlikely to bring strong impact. However, we also heuristically observe more coverage on green economy around major international political events in 2017 such as the US withdrawal and The 2017 United Nations Climate Change Conference (COP23).
  

6. Critically analyse your data and pipeline for potential bias and problems. What would still need to be done for the analysis to be trustable?
   
- Unable to open and distribute the dataset​ due to license restrictions
- Data representativeness is unguaranteed as I do not own access to the complete archive for data collection
- Distant reading can be restricted to understanding the material compared to close reading
- Reliance on pre-built computational without substantial fine-tuning can lead to bias
