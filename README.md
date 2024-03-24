# Climate change media discourse in Hong Kong: an analysis of Southern China Morning Post (SCMP) between 2016-2017 <br>
Anh Duong Nguyen

This repository is a sandbox for the final project of Computational Literacy course (LDA-H305) given by [Eetu Mäkelä](https://jiemakel.gitbook.io/cl4hss) in 2022 (autumn term, period 2). 

1.	Background and research question

The research question is **How does the Hong Kong-based electronic newspaper Southern China Morning Post (SCMP) present climate change issues?** This is an investigation of digital environmentalism in Asia, aiming to implement computational analysis tools/methods to explore discourses of climate change in electronic news. More specifically, I explored longitudinal patterns in climate change online news coverage and identified common themes and frames of climate change using a novel sample, with inspirations from Hase et al. (2021), “Climate change in news media across the globe: An automated analysis of issue attention and themes in climate change coverage in 10 countries (2006–2018)” and Broadbent et al. (2016), “Conflicting climate change frames in a global field of media discourse”. The analysis sheds light on climate change discourses in Hong Kong (SCMP), which existing cross-country studies of climate change journalism have overlooked.

2.	Data

Online news articles of the outlet with the keyword “climate change” from 01/09/2016-31/12/2017 were obtained from Nexis Uni with the archive’s engine search. The dataset is not openly accessible according to [Terms and Conditions for accessing Nexis Uni](https://guides.lib.uchicago.edu/lexisnexis#:~:text=Sciences%2C%20Social%20Sciences-,Terms%20and%20Conditions%20for%20accessing%20Nexis%20Uni,not%20permitted%20under%20our%20license), however, the aggregated analysis results can be found in this repository. 

During the selected timeframe, several important international events occurred: the Paris Agreement (2015) came into force on 4th November 2016, which was followed by the presidency of Donald Trump and the withdrawal of the US from the accord (June - September 2017). 
The collected dataset contains 255 entries (in separate text files) with metadata (published date, word count, and several topic/industry/geography labels) and articles' contents (title and body text). To preprocess the data for analysis, three procedures were carried out. (More details can be found [here]())

- Extracting metadata and content from individual entry files
- Lematizing words in articles' title and body text using stanza lemmatizer
- Constructing a concept network of labels and articles (label A with article 1 is connected if label A is annotated to article 1 with more than 80% confidence (heuristic threshold) 

3. Analysis
   
The analysis was done exploratively, with three aspects to consider: the volume of media coverage, the content (word-level and topic-level), and the fluctuation over time of these two features. Though they are intertwined in the analysis, it is divided into two parts, one focusing on media volume is available [here]() and another part on quantitative content analysis can be found [here]() (both include the source code and visualized results).

For more detailed analysis and discussion, read the manuscript [here]().

