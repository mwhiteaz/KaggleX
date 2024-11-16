#
**Using AI to Advance Educational Equity: Streamlining Compliance in Education Funding**

- This chatbot uses AI (via large language models) to assist school districts that enroll high percentages of students living below the poverty line. This tool is designed to answer both policy-related inquiries and implementation tasks associated with federal education funding compliance.  The chatbot can answer questions directly related to federal education legislation, currently called Every Student Succeeds Act (ESSA). It uses natural language processing techniques to analyze the underlying ESSA information to produce informed responses.
- The aim is to create a resource that enables various stakeholders to easily find answers to fundamental questions, such as, “What is Title I?” and, eventually, more complex queries like, “I’m a new principal; what should I do now?”  Intended audience includes state-level administrators and school district staff as well as parents within a Title I school or a scholar wanting to better understand U.S. school funding. 




##
**Project Features** 

- Programming Language: Python
- Libraries installed: Hugging Face Transformers, LoRA (Low-Rank Adaptation), Pandas, NumPy, Gradio
- Data sources: CSV file of question and answer pairs; RAG (Retrieval-Augmented Generation) implementation with context in an XLS format
- User Interface: Gradio for interactive querying





##
**Installation**

- Clone the Repository: Download the repository files to your local drive
- Install required libraries
- Load models including  Gemma 2-2b and Gemma 2-2b-it along with necessary configurations for fine-tuning using LoRA and Langchain for RAG implementation.




##
**Usage**

- Run the notebook: Open the notebook in Google Colab or Kaggle
- Launch Gradio interface: test prompts and interact with the model
- Documentation: Detailed installation instructions and rationale are included in notebook for reference





##
**Acknowledgements**

- This project was developed as part of the **KaggleX Fellowship Program, Cohort 4**.
- Special thanks to **George Williams, IEEE**, for his mentorship and guidance throughout this project.

