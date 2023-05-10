### Reasons for deprecation

For the specific model hyperparameters used in the poster, the results actually showed an improvement and decrease
in False Positives for Normal.
Therefore we assumed the model worked the way we wanted it to and made the poster.
However when we reapeated the training with a larger batch size in order to save the checkpoints, we found that
the results were not up to standard and it caused the model to be worse. 
Therefore we decided to change the project completely as we did not want to present cherry picked data.
Below are the results from running the baseline and modified model on batch size 512 and 15 epochs.

Baseline
Accuracy: 0.8292134831460675
[274, 29, 26],
[20, 221, 29], 
[17, 31, 243]


Modified 
Accuracy: 0.8247191011235955
[286, 53, 31], 
[8, 207, 26], 
[17, 21, 241]
