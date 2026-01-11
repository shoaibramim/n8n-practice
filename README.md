# n8n Practice Workflows

This repository serves as a collection of automation workflows created with n8n. The goal is to explore various integrations, AI capabilities, and data processing techniques using n8n's visual workflow editor.

## Repository Structure

To keep the workflows organized and easy to navigate, each automation project is placed in its own dedicated folder. This structure allows for detailed documentation specific to each workflow.

Each folder contains:
1.  **Workflow JSON File**: The actual n8n workflow file that can be imported directly into your local or cloud n8n instance.
2.  **README.md**: A specific guide for that workflow, outlining:
    *   What the workflow does.
    *   Prerequisites (e.g., API keys, specific nodes).
    *   Configuration steps.
    *   How to run and test it.

## How to Use

1.  Navigate to the folder of the workflow you are interested in.
2.  Read the local `README.md` to understand the requirements and setup.
3.  Download or copy the content of the `.json` file.
4.  Open your n8n dashboard.
5.  Create a new workflow and select "Import from File" or paste the JSON content directly into the editor.
6.  Configure any necessary credentials (like API keys or tokens).
7.  Activate the workflow.

## List of Workflows

*   **Automated Telegram Bot**: A scheduled bot that sends knowledgeable DSA tips in the morning and jokes at night using Gemini AI.
