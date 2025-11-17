# textGeneration-

## Project Description:
Build a character-level or word-level text generator that learns to write in a particular style
using RNN/LSTM.

## Architecture Explanation
Embedding layer followed by two LSTM layers,
A dense softmax output over the character vocabulary,
Training sequences are created from sliding windows of 40 characters,
Is trained using categorical cross-entropy with the Adam optimizer

## How to Run the Code
Upload the .ipynb file to Google Colab then run all the cells, use generate_text(seed_text, length, temperature) to generate text. You can also change the text that the model learns from by changing 
the string within "text". 

## Results and Analysis
Since the text is text from Shakespeare the model learned some basic structure and had some fragments of Shakespeare. However is still mostly noisy and repetitive, maybe a larger dataset 
and letting the model train for more time might lead to better results. 

## Team member contributions
Finished at home alone since class time was cut short.
