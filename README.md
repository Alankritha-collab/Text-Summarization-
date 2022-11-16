# Text-Summarization-
Text Summarization is a technique of Natural Language Processing that converts any information into a simple and short summary. In this Project, we have used different NLP-based Machine Learning Algorithms like the Word Frequency-based algorithm, Luhn algorithm, LexRank, and TextRank algorithms. 
MAJOR PROJECT PHASES 
Phase 1:-Implementing Extractive Approaches of Text Summarization using NLP Algorithms
Phase 2:- The working of Speech Assistor


MAJOR PROJECT_PHASE1_EXTRACTIVE_TEXT_SUMMARIZATION.IPYNB
	THIS FILE IMPLEMENTS:- Five Algorithms of Extractive Text Summarization like
1) Word-Frequency Based Algorithm 
2) LUHN Algorithm
3) Text Rank Algorithm
4) Lex Rank Algorithm
5) Cosine Similarity 
OUTPUTS    
The algorithms generate summaries and bar graphs from URLS of websites/research paper PDF/entertainment blogs/educational blogs/news articles.

	FETCHING_COMMON_SUMMARY.IPYNB
For fetching the common summary from above Algorithms, Cosine Similarity is used to calculate the similarities between the summaries produced by the Algorithms.
OUTPUT  ( for Instance)
Algorithm1:Algorithm2	0.86
Algorithm1:Algorithm3	0.92
Algorithm1:Algorithm4	0.92
Algorithm2:Algorithm3	0.91
Algorithm2:Algorithm4 	0.91
Algorithm3:Algorithm4	0.91



Execution Flow 
1) Execute sum_1
2) Execute sum_2
3) Execute sum_3
4) Execute sum_4
After Executing the above, execute fetching_common_summary.ipynb

OUTPUT
Produces common summary

MAJOR_PROJECT_PHASE2_SPEECH RECOGNITION.IPYNB
	This phase is the implementation of  Speech Assistor, which is incorporated with real time features 
	Speech Assistor fetch URLs from google front page and automatically generates the summary 
	It can open Wikipedia and YouTube videos automatically without any manual efforts of the user by using SELENIUM. 
	It reads out the facts and jokes  
	The most important feature that differs this Speech Assistor with other Assistors is Text Summarization, where a common summary is produced by Cosine Similarity is read by this Speech Assistor.
fetching the common summary through speech recognition.ipynb has to be executed for speech assistor to read the common summary  
