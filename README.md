# Language-Identifier-Bigram-NLP

The source code is in three files:
- letterLangId_thetazaps.pynb
- wordLangId_thetazaps.pynb
- wordLangId2_thetazaps.pynb
    
# HOW TO RUN:
To run the notebook, first make sure that your test data and train data is in the same directory as the notebook and labelled "LangId.train.English", "LangId.train.French" and "LangId.train.Italian" for English, French and Italian text respectively. The test data should be called "LangId.test" and the output will be in "letterLangId.out", "wordLangId.out" and "wordLangId2.out" respectively for the programs. The code can be run just by running the cell the code is in and the accuracy of the language model will be displayed in the notebook.

# PURPOSE OF CODE:
The general purpose of the three notebooks is the same which is to train data of three different languages (English, Italian and French) and use it to predict the language of the test data using a bigram model. The only difference is the tokens. letterLangId trains over bigrams of letters and wordLangId trains over bigrams of words. Both use alpha-1 smoothing. wordLangId2 also trains over words but uses Good Turing Smoothing.
