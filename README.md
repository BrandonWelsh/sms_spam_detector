## Information
Written by: Brandon Welsh

Start date: 3/31/2024 8:00pm

Due date: 4/8/2024 11:59pm

## Program Goals
"You'll be refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, you will create a Gradio app to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance." 

(copied from BootcampSpot Module 21 Challenge Overview)

## Dependencies
pandas, sklearn, gradio

## Setup Instructions
Run pip install pandas, sklearn, and gradio before running program (if you do not already have these libraries).

Next, run the following:

import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.pipeline import Pipeline
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.svm import LinearSVC
import gradio as gr

## How to use
Run each jupyter notebook cell. That's pretty much it.

## Resources Utilized
This section is dedicated to keep track of what I used to help complete this project:

50% sms_text_classification_solution.ipynb (this notebook had much of the required code already written into it, it was just a matter of copy paste)

40% class notes (I was able to use the class notes to fill in the rest of the program)

10% Artificial Intelligence (I used microsoft copilot to help debug the gradio application, I had a minor typo earlier in the program)

## Bugs

The application doesn't seem to work very well, and I'm not sure if the results are what was expected, or if I should have spent more time tuning and improving the model.

## Update Log
3/31/2024: Created github repo, took a look at the instructions.

4/3/2024: Created and called sms_classification, have no idea if it's working yet. I will test it properly later.

4/6/2024: Finished the project.