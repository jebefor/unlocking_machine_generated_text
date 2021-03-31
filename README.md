# Unlocking Machine Generated Text

This analysis was originally done as part of my work in automated-text detection for The Newsroom/Omdena. 

The main goal was to determine how close are generative model outputs to actual human text in order to improve our ML models with feature engineering. 

For that, I took a series of linguistic features common in the literature for both fake news and machine-generated text detection. 

The analyzed features are sentiment, subjectivity, readability, punctuation, and verb/noun use. 

The data is comprised of a balanced subsample of 5,000 GPT-2 small (model) outputs and 5,000 GPT-2 XL (model) outputs, all trained in Web Text, as well as 5,000 samples of Web Text itself.

Results are consistant in all tests: both generative models compare to human numbers. 

Further analysis on feature engineering possibilities could help improve Machine Learning models' performance for this task - in the above-mentioned project, we could achieve 70% F1-score with TF-IDF inputs.
