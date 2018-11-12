# NLPAssignment2
Part1 : Implementing HMM using brown-corpus , Part2 : One vs all logistic regression

Part1 

Implement a HMM using the Brown Corpus (you could import it from nltk). You may use the tagged corpus to calculate the transistion and emission probabilities. Note: Consider trigrams (the previous 2 tags) while calculating the transition probabilities, and bigrams (the previous word as well for a given tag) for the emission probabilities. 

Using these computed values, find the probability of the observation sequence given the parameters using Forward, Backward procedure followed by viterbi. For this part of the experiment, you must use the untagged Brown Corpus (consider an 80:20 split). 
Next, given the observation sequence, find the best fit "tag" sequence. For each tag, print out the top 50 words (most probable) emitted by it. Use random initialisations for the initial state probabilities.

Part2

Just like in Part1, perform POS Tagging on the Brown corpus. (Like before, train your Logistic Regression model on the, (tagged corpus, and test on the untagged one),Use one vs all logistic regression to perform this exercise. Essentially, given a word, try to classify it with classifiers trained for all pos tags and get most probable one.Do NOT use any ML libraries like scipy for coding up the logistic regression. NLTK maybe allowed, but only for getting corpus.
