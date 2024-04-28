# Osteoarthritis-Benchmark
This repository is mainly consisted of three branches: 

1.Osteoarthritis dataset

ltemQA.json--GIQA;

Real case QA.json--RCQA;

Treatment decision QA 1213.json--TSQA;

treatment based QA.json--MOQA;


Guideline-item QA (GIQA), which was developed based on specific items extracted from the clinical guidelines, evaluates the LLMs’ knowledge of these well-established standards. The GIQA comprised 337 items.

Real-case QA (RCQA) included treatment recommendations for 80 real-world patients. The RCQA, which comprised 80 items, evaluated LLMs’ capability in formulating treatment recommendations in a more complicated scenario in which individual information is provided, mirroring real-world clinical decision-making.

Treatment strategy QA (TSQA), which included treatment recommendations for different patient populations, provided treatment recommendations based on the patient’s age, clinical presentation, and other factors. The TSQA, which comprised 216 items, evaluated the capability of LLMs to derive treatment recommendations for specific patient types.

Management options QA (MOQA) included summarised recommendations for specific treatments from the included clinical guidelines.The MOQA, which comprised 145 items, evaluated LLMs’ knowledge of specific treatment options, as well as their ability to summarise medical evidence.

2.Codes and prompts to test and set up LLMs and DocOA

The file 'Prompt': COT prompting and IO prompting mentioned in the manuscript.

The file 'Test code': To test the LLMs (GPT-3.5 and GPT 4.0) and DocOA to ensure responses are given without bugs.

Test code_GPT.ipynb--To test GPT-3.5 and GPT 4.0.

Test code_Retrieval.ipynb--To test DocOA.

Structure transfer.ipynb — Transfer all the responses into JSON format.

3.Crude data from our initial tests

All outputs from the LLMs are copied and pasted into Excel files. Files whose names end in 'retrieval' are outputs from DocOA.

Other information：

The file 'Supply' includes the codes involved in the study, the prompts, and the model's output.

For any queries or feedback, please contact geteff@wchscu.cn


