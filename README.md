# DLAI 4
In this assignment we made a GPT model on economic data for scandinavian countries.
The data consists of GDP, inflation (CPI) and unemployment
We also make this data into summaries in sentence format, to provide a more fitting context for the GPT model

We then populate the knowledge graph with the tabular data. We create this grpah to provde the GPT model with additional context for question-answering.

For the GPT model, we give it a combined context of using the summaries.txt file and the knowledge graph.
Assigning the role that it is an agent that is trained to analyze economic data for scandinavian countries. 

Everytime we ask the agent a question it queries the knowledge graph and the summaries.txt to give a response. 



