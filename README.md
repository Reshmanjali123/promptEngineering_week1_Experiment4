# promptEngineering_week1_Experiment4
# Prompt Failure Diagnosis

## Aim
To identify and diagnose prompt failures in Large Language Models (LLMs), understand their causes, and improve prompts to generate better responses.

## Problem Statement
This experiment examines three common prompt failure types:
1. Hallucination / Factual Error
2. Instruction Ignoring – Format Constraint
3. Over-Refusal / Safety Mis-fire

## Technologies Used
- Python
- Google Gemini API
- Google Gen AI SDK

## Project Structure
```text
Prompt-Failure-Diagnosis/
├── main.py
├── Prompt_Failure_Diagnosis.ipynb
├── requirements.txt
├── .gitignore
└── output/
    ├── output_1.png
    ├── output_2.png
    └── output_3.png
```

## Installation
Install the required library:

```bash
pip install -r requirements.txt
```

## API Key Setup
1. Create a Gemini API key using Google AI Studio.
2. Set the `GEMINI_API_KEY` environment variable securely.
3. Never upload your API key to GitHub.

## Execution
Run the Python program:

```bash
python main.py
```

If using Google Colab, open `Prompt_Failure_Diagnosis.ipynb` and execute the cells in order.

## Expected Output
For each case, the program displays:
- Original prompt and model response
- Failure diagnosis and suspected cause
- Corrected prompt and improved response

Execution screenshots are stored in the `output/` folder.

## Conclusion
This experiment demonstrates how clear instructions, factual verification, and appropriate context can help improve prompt quality. Actual model responses must be examined to determine whether a failure occurred.

## Author
Student – B.Tech
