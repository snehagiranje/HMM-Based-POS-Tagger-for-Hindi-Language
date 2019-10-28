# HMM-Based-POS-Tagger-for-Hindi-Language

Part of Speech tagging in Indian Languages is still an open problem. We still lack a clear approach in implementing a POS tagger for Indian Languages.Here is a Hidden Markov Model based Part of Speech Tagger. POS tag set is used for the development of this tagger.

HMM(Hidden Markov Model) based POS Tagging in Hindi is done using Supervised and Unsupervised learning.

The supervised POS tagging model require a pre-tagged corpora which are used for training to learn information about the word-tag frequencies, rule and tagset, etc. The performance of the models generally increases with the increase in size of these corpora.

The unsupervised POS tagging models do not require pre-tagged corpora. Instead, they use those methods through which automatically tags are assigned to words like the Baum-Welch algorithm to automatically include tag sets, transformation rules etc. 


Usage eg : python supervised.py 0 ./data/hindi_testing.txt
