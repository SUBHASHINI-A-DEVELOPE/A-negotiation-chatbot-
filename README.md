# A-negotiation-chatbot-
This is an AI-powered chatbot for simulating product price negotiations. It allows users to interact with a chatbot that responds based on the product's price, features, competitor pricing, and customer loyalty. The chatbot adjusts prices dynamically within a set negotiation range.

Key Components:
Streamlit Interface:

The chatbot interacts with users via a chat interface.
Users can make offers or send messages, and the chatbot responds with price negotiation tactics.
Product & Competitor Price Simulation:

The chatbot is designed to negotiate the price of a specific product.
Competitor prices are generated randomly to simulate market competition.
AI-powered Negotiation:

The chatbot uses the Google Gemini API to generate responses based on the current state of the negotiation (price, features, competitor prices, customer loyalty).
A fixed number of negotiation rounds (7 by default) limits the interaction.
Negotiation Process:

The chatbot evaluates user offers based on predefined discount limits.
It provides persuasive responses, highlighting product features and addressing competitor prices.
