# Natural Language Processing Workshop
DSC (Developer Student Clubs) NUS Tech For Good Workshop is an annual workshop conducted by technology associates in DSC, a student-run club in NUS. Through this workshop, we equipped ~50 participants, who are students from various faculties in NUS, with an introduction to Machine Learning, along with some sample code and some basic projects for them to work on.

All of the resources (code, slides) are available in the "Participant Resources" folder.

This workshop is broken down into 3 segments, with further detail below:

1. Theory segment
2. Aggregating restaurant Reviews using NLP
3. Identifying Covid related on social media posts & news articles

### Theory
Covered topics such as fundamentals of Machine Learning, what Natural Language Processing is, how data cleaning works and more. The purpose of this segment was a short theory segment to get participants interested but not bored, especially for those from non computing backgrounds.

### Aggregating Restaurant Reviews using NLP
In this segment, we selected various restaurants in and around NUS that have their reviews available on Google Reviews. Then, we scraped the data from the reviews and provided it to the participants in a Excel file. THe idea was to have familiar restaurants for NUS students for them to test out the NLP on the restaurant's reviews. Through the Jupyter notebook, we guided participants through the following:

- Cleaning texts
- Creating a "Bag of Words" by filtering out unnecessary/conjunction words (e.g. "is", "I", ...)
- Splitting Training vs Test set
- Generating a Confusion Matrix using a Naive Bayes model to ascertain positivity or negativity of the review.

The algorithm was a simple one, by detecting key words that could be attributed to a positive/negative review of a restaurant, such as comments about its food, hygiene or the experience of the reviewers, and assigning an overall "positive" or "negative" value.

### Predicting whether social media/news outlet posts are about Covid-19
In this following segment, we left it to the participants to get a more hands on experience with predicting whether social media/news outlet posts and articles are related to Covid-19. The idea was inspired by Instagram & Facebook's response to Covid-19, detecting whether posts were about the virus and labelling it with additional information. We wanted to get participants to replicate a simple model of it, with the sample code in the "NLP Contest" folder.

![image](https://github.com/brian16600/Machine_Learning_2_Workshop_Repo/assets/83962069/4a1e1f49-6368-4232-a149-7a345a24e6c8)

We provided participants with a dataset consisting of various texts, some related to Covid-19 and some not, that we had scraped off the Internet and social media. The method to develop the model was the same as the previous section, and during our own testing we managed to get 70+% accuracy in predictions based on keywords.

