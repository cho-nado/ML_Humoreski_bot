# ML_Humoreski_bot

## Team:

* Djaga Artem М8О-107М-23
* Zorina Anastasia М8О-107М-23
* Stulov Ilia М8О-107М-23

# Task Distribution

1. Anastasia Zorina was responsible for training the model, collecting the dataset, and conducting tests.
2. Artem Dzaga handled the backend of the Telegram bot, the integration of the trained neural network, and the creation of the architecture.
3. Ilya Stulov was in charge of problem definition, collecting metrics, system evaluation, and the frontend of the Telegram bot.


## How can this bot help?
Imagine you’re texting someone you have romantic feelings for. The conversation feels a bit dry, but since you’re too busy thinking about how wonderful this person is, you can’t come up with a joke to lighten things up. That’s where our bot comes in. You type in the beginning of a story you were discussing with your partner, and it generates a joke. You send it to your love interest, and bingo! They smile, creating a happy and fun association with you.

Another scenario: you’re in the middle of a heated debate in the comments section of a post or tweet. You’ve laid out tons of arguments supporting your point, but to seal the deal, you need a witty, sarcastic remark to put the other person in their place. Some philosophers and scholars argue that humor is a passive form of aggression, and this is exactly one of those cases. You send the bot the topic of the discussion, it generates a joke, you post it in the comments, and voilà! You’re on top.

The bot only works in English, designed this way so you can get jokes on an international level.

The bot is free!!!

## The architecture of our Telegram bot consists of the following key modules:

1. Natural Language Processing (NLP): Interprets user input, intent, and tone using pre-trained language models and generates responses based on extracted information.
2. Knowledge Base: Stores factual data, providing answers to user queries and supporting response generation. It can be updated dynamically or pre-filled.
3. Machine Learning Component: Trains models for tasks like humor generation, sentiment analysis, and language translation using the LlamaIndex library, continuously improving with user feedback.
3. Internal Data Storage: Maintains the history of user interactions.
4. Dialogue Deployment Engine: Manages Telegram interactions and uses Google Collab for chat deployment.
5. Humor Generation Module: Creates humorous responses using machine learning models, employing techniques like wordplay and puns, adapting based on user feedback.
6. User Interface: Provides a simple, responsive interface for user interaction.
7. Feedback System: Allows users to rate responses, helping improve the humor generation process.

## Machine Learning Component

We are building a joke generator using the GPT-3 model, which is a powerful text generation model with 175 billion parameters, 96 layers, and 96 heads per layer. GPT-3 was chosen for its ability to generate high-quality responses with minimal examples. We trained it on a dataset of 4,500 jokes, including anecdotes and funny dialogues.

Initially, we experimented with an LSTM (Long Short-Term Memory) model, an improved version of RNN (Recurrent Neural Networks), designed for sequential data. However, LSTM struggled with generating coherent text, prompting us to switch to GPT-3 for better performance.

## System Evaluation Summary

We integrated our neural network with the Telegram bot and tested its performance through multiple user interactions. A dedicated server was set up to ensure the bot was always accessible. We tested the system with a variety of query types, both personal and general, including implicit and explicit joke-related requests.

We evaluated the bot's latency and response generation for queries of varying complexity and for multiple users simultaneously. Feedback from friends and colleagues was mostly positive, praising the bot’s performance, grammar, and use of humor, including wordplay.

However, some negative feedback highlighted that the bot occasionally struggled with implicit joke-related queries and real-life scenario jokes, sometimes generating responses without humor. This could be improved by expanding the joke database and adding more examples of puns, life situations, and sarcastic responses. A "thumbs up/thumbs down" joke evaluation system would also help refine humor generation, adapting to individual user preferences.

In the future, with a larger user base, we plan to analyze user experience metrics (like session activity) and bot quality metrics (such as the frequency of incorrect responses).




