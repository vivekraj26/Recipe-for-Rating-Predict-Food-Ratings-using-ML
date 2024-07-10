Data Files
The dataset is composed of the following files:

train.csv: The training set, which includes the target variable 'rating' and accompanying feature attributes.

test.csv: The test set, containing similar feature attributes but without the target variable 'rating' , as it is the variable to be predicted.

sample_submission.csv: A sample submission file provided in the correct format for competition submissions.

Columns Description

RecipeNumber: Placement of the recipe on the top 100 recipes list
RecipeCode: Unique ID of the recipe used by the site
RecipeName: Name of the recipe the comment was posted on
CommentID: Unique ID of the comment
UserID: Unique ID of the user who left the comment
UserName: Name of the user
UserReputation: Internal score of the site, roughly quantifying the past behavior of the user
CreationTimestamp: Time at which the comment was posted as a Unix timestamp
ReplyCount: Number of replies to the comment
ThumbsUpCount: Number of up-votes the comment has received
ThumbsDownCount: Number of down-votes the comment has received
Rating: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable)
BestScore: Score of the comment, likely used by the site to help determine the order comments appear in
Recipe_Review: Text content of the comment
