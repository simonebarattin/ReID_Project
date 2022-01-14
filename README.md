# ReID Project
The following is a University project in which we were asked to complete two task, starting from the Market-1501. In the repository you can also find a report with the description of the adopted solutions.
## Classification Task
Each image in the dataset has 28 attributes, such as *id, gender, hair, up, down, clothes, hat, backpack, bag, handbag, age, up_color* and *down_color*, where the last two contain 8 and 9 colors respectively. The first task of this assignment then is to build a
multi-class classification model to predict these attributes.
The notebook used for the first task is *classification_task.ipynb* and the predictions obained in for the test set is contained in classification_test.csv.
## Person Re-Identification Task
In the second task we were asked to build a person re-identification model to retrieve from the test directory all the images depicting the same person identity appearing in a given query image. More formally, for each image in the queries directory, we produce an ordered list of images from the test directory that the model believes corresponds to the same person identity depicted in the query image.
The notebook used for the first task is *reid_task.ipynb* and the predictions obained in for the test set is contained in reid_test.txt.
