# Generative Social Choice Dataset

This repository contains the data we collected for the Generative Social Choice project. We ran two experiments on Prolific asking 100 individuals each about their opinions on chatbot personalization. In the first experiment, we ask individuals about their opinions on personalizing AI and then ask them to rate summary statements of other people's opinions about personalizing AI. In the second experiment, we ask individuals to rate summary statements of other people's opinions about personalizing AI.  The anonymized data is included in this repository.

Sara Fish, Paul Gölz, David C. Parkes, Ariel D. Procaccia, Gili Rusak, Itai Shapira, Manuel Wüthrich, https://arxiv.org/abs/2309.01291.

## Dataset Details

The following document details the columns in this dataset.

* user_id: This column includes an anonymized version of the user_ids.	


* step: This column represents the order in which the participants where shown the questions.


* question_type: This column represents the question type for the current row. These include: "reading", "text", and "text + multiple choice".


* question_text: This column includes the question text.


* button_label: For questions with buttons, this column includes the label on the button.	


* json_choices: For questions with choices, this column includes the labels of the distinct choices.	


* choice: For questions with choices, this column includes the choice that the user chose.	


* choice_numeric: For questions with choices, this column includes the numeric representation of the choice that the user chose.


* text: For questions with text responses, this column includes the user's text response.	


* answer_date: This column includes the date that the user completed the survey.


* sample_type: This column includes the sample type: generation or evaluation.
