# Propaganda Detection Model
This repository provides resources and information on the Propaganda Detection Model, which demonstrates how findings from the SemEval 2020 Task 11 can be combined. The model implements various approaches from the challenge, leading to superior performance in Micro F1-Score compared to individual techniques used during the challenge.

# Research Question
How can the findings of the SemEval 2020 Task 11 be combined, and to what degree (in terms of Micro F1-Score) will this combination be able to compete with the results of the technique classification subtask?

# Findings
The Propaganda Detection Model performs with a Micro F1-Score of approximately 0.78. This was after the combination of various approaches from the challenge. Regrettably, due to the closure of the test data evaluation by Da San Martino et al., I am unable to score the model on test data.

Given the circumstances, the research question could only be answered based on the scores achieved on the development dataset by the participants. For a detailed comparison, please refer to my master thesis, which lists the top five submissions. Note that one submission that only appeared on the development dataset (without an accompanying paper) has not been considered, even though it achieved a Micro F1-Score of 0.6717.

Comparing our model's Micro F1-Score of around 0.78 to the evaluation scores of the best five submissions (0.7), it's evident that our model exhibits superior performance. Furthermore, the developed Propaganda Detection Model does not produce any zero-predicted classes, which illustrates the effectiveness of combining different techniques used by the participants.

# Conclusions
My work provides evidence that the combination of different techniques used by the participants during the SemEval 2020 Task 11 challenge leads to even better results in terms of Micro F1-Score. This development and the resulting Propaganda Detection Model provides a solid foundation for further advancements in the field.


# Limitation
Please bear in mind: The Propaganda Detection AI.ipynb is consolidated version of my code. The whole code for the Master Thesis was around 16k lines. 
Right now, the notebook is not runnable, since multiple notebooks were consolidated to one big notebook for demonstration reasons.
Further, code from a local IDE was copy/pasted without checking it's functionality. 
For example, the scrappy cells can't work, since I copied only the spider, but nothing else.


Further, I did not have the time to create a meaningful story around the code. 
If you are evaluating my skills because of hiring:
- I know how to create classes to remove repetitive code, but sometimes it's easier in Notebooks to work with repetitive cells (for debugging reasons). :) 
- I know how to document code. :)
- I know how to test code. :)

  
Thank you for reading this.
