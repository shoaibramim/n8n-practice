# Automated Telegram Bot with Timely Joke or Fact

This workflow automates the process of sending messages to a Telegram chat based on the time of day using Gemini AI.

## Features

*   **Morning Schedule (10 AM)**: Sends a knowledgeable tip about Data Structures and Algorithms (DSA) or System Design to help strengthen coding skills.
*   **Evening Schedule (10 PM)**: Sends a random, witty joke related to programming or technology to lighten the mood.
*   **AI Integration**: Uses Google's Gemini AI to generate unique content for every execution.

## Prerequisites

To run this workflow, you need:

1.  **n8n**: Installed locally (e.g., via Docker) or cloud-hosted.
2.  **Google Gemini API Key**: Obtainable from Google AI Studio.
3.  **Telegram Bot Token**: Create a bot using @BotFather on Telegram.
4.  **Telegram Chat ID**: The ID of the user or group where messages will be sent.

## Setup Instructions

1.  **Import Workflow**: Import the `Fun Tel Bot.json` file into your n8n workspace.
2.  **Configure Credentials**:
    *   Add your Google Gemini API key to the HTTP Request node (or use a credential if configured).
    *   Add your Telegram Bot Token to the Telegram node credentials.
3.  **Set Chat ID**: Update the `Chat ID` field in the Telegram node with your specific ID.
4.  **Adjust Timezone**: Ensure your n8n workflow settings are set to your local timezone so the schedules trigger at the correct local time.
5.  **Activate**: Toggle the workflow to "Active" to enable the automated schedule.
