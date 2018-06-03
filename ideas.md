## Exercise Goals

- Exercise on learning new algorithms for ML
- Exercise on designing an ML system
- Exercise on evaluating an ML system
- Exercise on visualizing results of an ML system

## Exercises

- Yelp review prediction
    - Predict the stars given the review text
    - What are important features for each star rating?
    - Talk about bias in your results
        - Analyze which businesses get mispredictions
    - TODO: figure out a real world application of this to analyze harm
    - How does your error change for various types of businesses? (VISUALIZE)
        - By city
        - By review_count
        - stars (of the business)
        - categories
    - based on: http://nyc.lti.cs.cmu.edu/classes/11-741/s18/HW/HW5/HW5.pdf

- Sentiment Analysis (DESIGN)
    - Create a sentiment classifier for the sentiment140 dataset
        - http://help.sentiment140.com/for-students/
    - Is the dataset balanced?
    - Look at different ways of vectorizing the dataset
    - How well does the classifier work on the Claritin Twitter dataset?
        - https://www.figure-eight.com/wp-content/uploads/2016/03/1384367161_claritin_october_twitter_side_effects-1.csv
    - Even though these are also tweets, why the discrepancy?
    - How does performance compare across different genders? (EVALUATE)
    - How does this effect change if you fine-tune your model on a subset of
      claritin's dataset?
    - How would you try to normalize the outcomes across gender?
    - If claritin was going to use your classifier to redirect support/research
      investments, how would false positives / false negatives have real-world
      impact?
        - How is this furthered by the discrepancy between genders?

- Conversation Bot
    - using the cornell movie dialogs dataset
    - train a seq2seq model
    - based on:
      https://github.com/chiphuyen/stanford-tensorflow-tutorials/tree/master/assignments/chatbot

- Geographic Hierarchies
    - Using compas or chicago crime data
    - predict arrest? or predict existence of crime?
    - 
