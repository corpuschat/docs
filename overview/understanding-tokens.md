# Understanding tokens
## Understanding tokens in the context of Large Language Models (LLMs) and how thay are used in Corpus

In the context of Large Language Models (LLMs) like those used in Corpus, tokens are a fundamental concept for measuring the usage of AI services. This document aims to clarify what tokens are and how they are utilized within Corpus, helping users understand their plan's token allocation and consumption.

[[info What is a Token?]]
Tokens serve as the units of communication that the LLM processes, whether it's understanding input (a user's prompt) or generating output (the chatbot's response). **A token is roughly equivalent to 3-4 characters or about three-quarters of an average English word.**
[[/info]]

## Token usage in Corpus

- **Allocation:** Each subscription plan with Corpus includes a monthly token allowance.
- **Training consumption:** Tokens are consumed during the training phase of your chatbot, contingent upon the volume of content the chatbot learns from.
- **Interaction consumption:** Every interaction with the chatbot, from the user's question to the chatbot's reply, results in token consumption.

## Token consumption rates

Different models within the Corpus platform consume tokens at varying rates:

- **Gpt-3.5 model (default):** Consumption occurs at the base rate determined by the length of content processed.
- **Gpt-3.5-turbo-16k model:** Tokens are consumed at twice the base rate due to the enhanced capabilities and data processing limits of this model.
- **Gpt-4 model:** The most advanced model available, consuming tokens at a rate ten times the base rate, reflecting its advanced reasoning and response generation abilities.
- **Gpt-4-turbo-128k model:** A variant of the GPT-4 Model, which can process context windows of up to 128,000 tokens (coming soon).

## Implications of token consumption

- **Budgeting:** It's important for users to monitor their token usage to stay within their plan's limits and avoid potential overages.
- **Model selection:** Choosing between the GPT-3.5-Turbo-16K and GPT-4 models involves a trade-off between the sophistication of the chatbot's responses and the rate of token consumption.

## Summary

Tokens are a critical aspect of using Corpus and its underlying LLM technology. By understanding token allocation and consumption, users can make informed decisions about training their chatbots, engaging with customers, and selecting the appropriate model for their needs. It is essential to consider the balance between desired functionality and token usage to maximize the benefits of the Corpus platform within the constraints of your selected plan.
