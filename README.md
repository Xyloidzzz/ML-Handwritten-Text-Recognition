# Handwritten Text Recognition

This is a little test to implement the things I learnt from my Machine Learning class.

I've set up main.py into cells for ease of running the code.

## Data

I used some data from Kaggle.
You can download it from [here](https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format).

## Output

First I displayed a bar graph of the number of elements we had per letter in the alphabet.

![number of elements for each letter of the alphabet](./images/output1.png)

Then we took the elements data and turned it into images we can plot for both humans and the computer to recognize.

![images displayed after data was formatted](./images/output2.png)

We then trained the model. Epochs = 10.

![running the model](./images/run-model.png)

Here is the output of:

```py3
model.summary()
```

![model summary](./images/model-summary.png)

Displayed out accuracy.

![accuracy of the model after running and before prediction](./images/acc-output.png)

And then made a prediction using our testing data.

![prediction for letter](./images/output3.png)

![prediction for letter](./images/output4.png)
