Since such operations can be repeated quite often, and a person will edit the transformation logic, it is desirable to save this data and have the ability to retrain on it. Propose an approach for retraining and try to implement such retraining on synthetic examples (you can come up with them using GPT =))

Expected result:

Code on GitHub using OpenAI API, Langchain, and other LLMOps tools of your choice.
An interface in which you can perform such an operation. Place the interface in the public domain for testing work

Example user journey:

The user uploads the Template table.

The user uploads table A.

For each column in the Template, the system suggests columns from column A (1 or more relevant candidates), showing the basis for the decision (formats, distributions, and other features that are highlighted in the backend).
The person confirms the mapping.

Next, the data transformation stage begins. The system generates and displays the code with which it will perform the transformation. The user can edit it and run it, checking the correctness of the mapping.

At the output, the user receives a table in the Template format (columns, value formats) but with values from table A.
The same for table B.

Your thoughts on edge cases and how they can be overcome
