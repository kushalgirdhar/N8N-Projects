WhatsApp Chatbot Workflow with n8n

This repository contains a WhatsApp chatbot workflow built using n8n. The chatbot processes incoming messages (text, audio, or images), classifies them, and responds in the requested format using an AI agent.


WORKFLOW OVERVIEW

Trigger: WhatsApp messages (text, audio, or images).
Process: Classifies input, handles media (e.g., transcribes audio, analyzes images), and generates prompts.
Response: Sends back a response in the format requested (text or audio).

https://github.com/kushalgirdhar/N8N-Projects/blob/main/Screenshot%202026-04-15%20122240.png

HOW TO USE

1. Clone or download this repository.
   
2. In your n8n instance, go to the workflows section.
   
3. Click the three dots in the upper right and select "Import from File.
   
4. Upload the whatsapp_chatbot.json file from this repository.
   
5. Activate the workflow.



SETUP REQUIREMENTS

1. An active n8n instance.

2. WhatsApp credentials configured in n8n for the WhatsApp Trigger node.

3. AI Agent credentials (e.g., OpenAI or similar) configured in n8n for text/audio generation.

4. Ensure any additional nodes (e.g., for audio transcription or image analysis) are properly set up with the required API keys.

Notes

> You may need to adjust node configurations based on your specific API keys and preferences.

> The workflow was created and tested as of June 9, 2025.

Feel free to contribute or modify the workflow for your needs!
