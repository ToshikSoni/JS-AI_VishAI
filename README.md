# Mental Health Support Chatbot

A supportive AI chatbot designed to help people experiencing distress and depression by providing empathetic conversation and mental health resources.

## Features

- **Empathetic Conversation**: The chatbot is designed to listen, support, and respond with empathy to users in distress
- **RAG Capabilities**: Integrates with mental health resources and PDFs to provide evidence-based information
- **Conversation Memory**: Remembers the context of the conversation to provide coherent support
- **Crisis Detection**: Identifies potential crisis situations and provides appropriate resources
- **Calming UI**: A soothing, accessible interface designed with mental health in mind

## Important Notice

This chatbot is NOT a replacement for professional mental health services or crisis intervention. If you or someone you know is experiencing a mental health emergency, please contact emergency services or a crisis hotline immediately.

## Setup Instructions

### Prerequisites
- Node.js (v14 or later)
- Azure account with OpenAI service enabled

### Environment Setup
1. Create a `.env` file in the root directory with the following variables:
   ```
   AZURE_INFERENCE_SDK_KEY=your_azure_openai_key
   INSTANCE_NAME=your_azure_openai_instance_name
   DEPLOYMENT_NAME=your_deployment_name
   ```

### Adding Mental Health Resources
1. Create PDF files with mental health information
2. Place them in the `data/mental_health_resources` directory

### Installation
1. Install dependencies:
   ```
   npm install
   ```

2. Start the server:
   ```
   npm start
   ```

3. In a separate terminal, start the web client:
   ```
   cd packages/webapp
   npm start
   ```

## Crisis Resources

- National Suicide Prevention Lifeline: 988 (US)
- Crisis Text Line: Text HOME to 741741 (US)
- International Association for Suicide Prevention: [https://www.iasp.info/resources/Crisis_Centres/](https://www.iasp.info/resources/Crisis_Centres/)

## Responsible Use Guidelines

This chatbot must be used responsibly and ethically:

1. Do not replace professional mental health services with this chatbot
2. Always ensure users are aware they are talking to an AI
3. Provide clear pathways to human help in crisis situations
4. Regularly review and update the mental health resources to ensure accuracy
