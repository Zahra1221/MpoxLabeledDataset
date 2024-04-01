# Mpox Labeled Dataset

The dataset shared in this repository, Mpox.csv, includes the tweets related to Mpox, posted from South Africa. The dataset has been manually labeled for stance-detection, and classified into three classes: Positive, Neutral, and Negative. Each class is defined as:

- Positive: In this class the authors of the tweets agree with the government's response to Mpox outbreak, and strongly support, and trust it.
- Negative: In this class the authors are unfaithful towards government's ability to contain and control Mpox.
- Neutral: In this class the authors did not believe in Mpox being a serious threat to public health, and refused to engage in discussions pertaining to government's response.

Due to [Twitter's deveoper agreement](https://developer.twitter.com/en/developer-terms/agreement-and-policy), only tweet IDs could be publicly shared; therefore, this dataset includes only two columns, namely, TweetID and Label. In order to have access to the actual tweet and other metadata such as created date and/or location, the tweet IDs need to be [hydrated](https://towardsdatascience.com/learn-how-to-easily-hydrate-tweets-a0f393ed340e).
This dataset should be used for non-commercial purposes only, as long as it is not redistributed. If you use our dataset in your work, please cite our manuscript:

Perikli N, Bhattacharya S, Ogbuokiri B, Movahedi Nia Z, Lieberman B, et al, Evaluating Automatic Annotation of Lexicon-Based
Models for Stance-Detection of M-pox Tweets, PLOS Digital Health, 2024;
