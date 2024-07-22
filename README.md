This project compares full fine-tuning and Parameter-Efficient Fine-Tuning (PEFT) using QLoRA. The comparison aims to evaluate the performance, efficiency, and practicality of each method for the text summarisation task. Python code used for this study are available in the provided Jupyter Notebook.

Fine-tuning pre-trained models is a common practice in machine learning to adapt a general model to specific tasks. However, full fine-tuning can be computationally expensive and time-consuming. Parameter-Efficient Fine-Tuning (PEFT) methods like QLoRA provide an alternative by only adjusting a small subset of parameters, aiming to achieve similar performance with lower computational costs.

The rouge metric is used to compare the original model with the fully fine tuned and PEFT model.
