# BIOSTAT626_mid1
In this experiment, it involves six different activities and six postural transitions that occurred between the static postures, which are three static postures (standing, sitting, lying), three dynamic activities (walking, walking downstairs, and walking upstairs), and six transitions (stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand).
Our goal is to classify the activities in the training data and use that to predict the activity in the test data.

In the first file, binary_4399, first, import your training data and the test data. The second chunk is binary classification, which your activity of the training data will be separate into two categories.
(static (0) and dynamic (1)).
Your training data will also be split into two set, training set and the test set, in order to test the accuracy of the prediction of your training data.
Then, the code will let you fit your model with glm. 
The third chunk is to use your predicted glm model to predict the binary classification activity of your test data.
The forth chunk will let you generate your predicted result of your test data with a txt file.



In the second file, multiclass_4399, first, import your training data and the test data. The second chunk is multi-classification, which your activity of the training data will be separate into seven categories.
[walking (1), walking_upstairs (2), walking_downstairs (3), sitting (4), standing (5), lying (6), and static postural transition (7)].
Your training data will also be split into two set, training set and the test set, in order to test the accuracy of the prediction of your training data.
Then, the code will let you fit your model with LDA. 
The third chunk is to use your predicted LDA model to predict the multi-classification activity of your test data.
The forth chunk will let you generate your predicted result of your test data with a txt file.
