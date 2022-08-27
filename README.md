# AURA Conversational AI for Mental Health (NLP, RASA)

# Description
- AURA - Conversational AI engages with the user, assesses the user’s mood, and develops real-time therapeutic conversations in which users can express their thoughts and emotions when they are feeling down. 

- Conversations are based on Cognitive Behavioral Therapy (CBT) treatment which aims at talking therapy that helps patients manage mental health conditions by changing the way they think and reframing their thoughts. 

- Mental health chatbots have stepped in with a promise to fill the gaps in the mental health care system. These conversational agents support patients to gain access to treatments without the fear of being judged while offering a high level of privacy and anonymity.

# Techniques
- AURA is trained with 55 Rules and 50 intents and 8 stories.

- RASA NLU is used to understand the language using intent classification, response retrieval, and entity classification

- Rasa Core determines which action to take from a predefined list. It uses machine learning models to train conversations to decide what to do next.

# Framework
- AURA AI is built on RASA Framework - rasa 3.0

- Model is evaluated based on user interaction using RASA interactive

- Model is served as a rest endpoint - Using Sanic Framework 

- Integrated with Telegram bot API to interact with model inferencing server.


# Dataset
- For the project data from multiple sources using Kaggle and Academic Publications are considered.

- AURA is trained with Multiple Clinical trial data sources.

- https://www.kaggle.com/datasets/nupurgopali/depression-data-for-chatbot
- https://paperswithcode.com/paper/a-computational-approach-to-understanding
- https://towardsdatascience.com/counsel-chat-bootstrapping-high-quality-therapy-data-971b419f33da
- https://paperswithcode.com/paper/towards-emotional-support-dialog-systems
