# judgements_dataset

We trained a model based on chinese-roberta-wwm-ext to extract relevant crime dates from Chinese court judgments. After training the model, we used it to predict the crime dates in all court judgments, and then extracted 5,000 cases where the crime occurred in 2014. We manually annotated the crime dates in these documents. 

Additionally, we used LLama 3.1-70B to predict the crime dates in these 5,000 documents to verify the accuracy of the model.

