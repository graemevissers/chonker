# chonker
A chatbot generating cat related content trained from a house group chat (AKA Kai)

TODO:
Model Training:
- Ingest all utterances from 'The Nook' and 'The Pit' Messenger chats
- Prepare Messenger corpus for training
- Train a GPT-2 generator on ingested Messenger corpus

Hosting:
- Configure AWS resources using Serverless
- Implement functionality for Lambda functions using Python
- Host trained GPT-2 generator (look into hosting options)
- Connect model with Messenger using API
