The dataset for this project can be acquired [here](https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/). Moreover, the GloVe word vector is provided by Stanford NLP group and can be downloaded [here](https://nlp.stanford.edu/projects/glove/)

## Contents

### Tools Required
The general requirements for this project are as follows:
- numpy
- regex
- tensorflow
- keras

### Preprocessing
Process data to remove and replace characters and words irrlevant for analysis to create a processed training and testing .csv file.
- **Process characters/words of each tweet with regex**: Remove punctuations, Convert more than 2 letter repetitions to 2 letter, Check if word begins with an alphabet, and lowercase all the words
- **Process Emoticons using regex**: Replace emoticons with strings 'positive' or negative'
- **Process Tweet with regex:** Remove twitter usernames beginning with @, remove URLs, and replace #hashtag with hashtag
      
