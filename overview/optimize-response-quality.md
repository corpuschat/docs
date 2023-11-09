# Optimizing chatbot responses
## Understanding AI-generated answers

In the realm of AI chatbots, ensuring accurate and relevant responses is crucial for user satisfaction and operational efficiency. One key challenge in this domain is avoiding "hallucinations," where AI provides incorrect or misleading information. This document outlines strategies to optimize chatbot responses, particularly for Corpus’ ChatGPT-powered support chatbot.

[[note Understanding Hallucinations in AI]]
AI hallucinations refer to instances where chatbots generate false or irrelevant information. These can damage customer trust and diminish the credibility of the service. To mitigate this, it's vital to fine-tune the chatbot's parameters and content.
[[/note]]

## Response optimization strategies

### Selecting the right personality

The first step to optimizing chatbot responses is to select or create a personality that matches the service goals:

- **Generic website assistant:** Suitable for general inquiries and guiding visitors.
- **Sales assistant:** Focuses on product benefits, ideal for lead qualification.
- **Customer support:** Provides detailed answers for customer assistance.
- **Technical support:** Offers in-depth responses, often with code examples.

Multiple chatbots can be deployed for different roles, such as a sales chatbot for lead nurturing and a support chatbot for post-purchase queries.

### Adding QA documents

Create a structured document for frequently asked questions, following this format:

- **Title:** The question itself.
- **Body:** A detailed, accurate response.

This helps in providing consistent and precise answers to user queries.

Additionally, create documents with clear instructions fo queties such as "How can I contact you?" or "Can I speak with a Human", and direct users to use the integrated contact form in the chat widget.

### Enhancing with links

Use markdown to add links to documents, guiding users to additional information on your website:

```markdown
[More about our services](https://www.yourwebsite.com/services)
```

### Custom prompt instructions

Incorporate specific instructions to tailor the chatbot's tone and style:

- **Pricing queries:** Prompt the chatbot to refer users to the pricing page.
- **Response style:** Include emojis or specific phrases to align with the brand voice.

### Integration with documentation

For customer or technical support chatbots, ensure documents link back to the documentation site to help the Chatbot provide deeper context.

Include code examples where relevant, to assist users with technical issues.

## Choosing the right LLM model

By default, Corpus uses the GPT-3.5 model. While its greate for most use-cases, we recommend consideting using GPT-4 when more nuance and sophistication is required.

While the GPT-4 model may require more investment in message credits, it is highly recommended for nuanced and complex response needs, such as:

- **Sophisticated responses:** GPT-4 can generate more detailed and context-aware replies.
- **Technical support chatbots:** It can provide accurate coding assistance and technical guidance.

## Summary

Optimizing chatbot responses is a dynamic process that involves selecting the appropriate personality, creating a detailed knowledge base, integrating with documentation, and choosing the right language model for your needs. By implementing these strategies, Corpus can deliver high-quality, reliable, and brand-consistent communication, enhancing the overall user experience.
