# Final submission for APLN 552 – Spring 2024

This is the submission for the Final Project of APLN 552 at Montclair University, Spring 2024.

## Environment Setup
Make a new Python virtual environment using venv and run `pip install -r requirements.txt`

## Running claude_prompts.ipynb
The only code included in this repo is "claude_prompts.ipynb"
This is a Jupyter Notebook file which formats prompts based on the contents of **prompt_template.txt** and quotes in **quotes.txt**

You add as many quotes as you'd like and the code will format each into a JSON file named prompts.json

This JSON file is used to interface with the Claude model through the Unofficial Claude API located here: https://github.com/st1vms/unofficial-claude-api

> [!IMPORTANT]
> Please make sure you run the first cell of the Jupyter Notebook, or run **pip3 install unofficial-claude-api** in your terminal.
> You must also be logged into https://claude.ai/ in your browser and have allowed cookies in order to interface with the mdoel through the API.

## Contents
+ *requirements.txt* – a list of required dependencies
+ *quotes.txt* – the list of quotes I used for this project
+ *prompt_template.txt* – the prompt template I used for this project
+ *final_write_up.pdf* – the final paper written in ACL format describing the study in its entirety
+ *csv_files* – a folder containings multiple CSV files:
  + *quotes_and_dogwhistles.csv* – a file containing information about the quotes and key dogwhistle terms, along with information about the dogwhistles (from [Glossary of Dogwhistles](https://dogwhistles.allen.ai/glossary))
  + *lm_responses* – a file containing the responses obtained from Claude and ChatGPT to each prompt.
  + *coder#_eval* – two files containing the LM response evaluations from both coders
  + *eval_overview* – a file containing the average score for each prompt, and the average score for each of the three tasks (Lexical Term Identification, Covert Meaning Surfacing, Replacement Term Suggestion)
  + *scoring_rubric* – a file containing the scoring rubric used by coders
