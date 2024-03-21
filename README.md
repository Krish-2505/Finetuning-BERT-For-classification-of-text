# Finetuning-BERT-For-classification-of-text
## Dataset classification of quora questions sincere/insincere

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

=>Has a non-neutral tone
=>Has an exaggerated tone to underscore a point about a group of people
=>Is rhetorical and meant to imply a statement about a group of people
=>Is disparaging or inflammatory
=>Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
=>Makes disparaging attacks/insults against a specific person or group of people
=>Based on an outlandish premise about a group of people
=>Disparages against a characteristic that is not fixable and not measurable
=>Isn't grounded in reality
=>Based on false information, or contains absurd assumptions
=>Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers
The training data includes the question that was asked, and whether it was identified as insincere (target = 1). The ground-truth labels contain some amount of noise: they are not guaranteed to be perfect.
### Data fields
qid - unique question identifier
question_text - Quora question text
target - a question labeled "insincere" has a value of 1, otherwise 0
### size of the Dataset
total text in dataset is around 13 lakh of which sincere(93 %) and insincere(7%)
### sample of dataset
![image](https://github.com/Krish-2505/Finetuning-BERT-For-classification-of-text/assets/120018777/62173e6f-5b61-46a0-8e70-c21e059d3517)

## demo of application
<img width="890" alt="Screenshot 2024-03-19 221815" src="https://github.com/Krish-2505/Finetuning-BERT-For-classification-of-text/assets/120018777/5c06826f-5451-4ee8-bda1-37a87b6a3770">
<img width="815" alt="image" src="https://github.com/Krish-2505/Finetuning-BERT-For-classification-of-text/assets/120018777/8e289007-c5b4-426e-9cbe-b18ae29259e1">
<img width="794" alt="image" src="https://github.com/Krish-2505/Finetuning-BERT-For-classification-of-text/assets/120018777/a9e8a960-558c-489d-adaa-9b0fc0cd8fbc">


