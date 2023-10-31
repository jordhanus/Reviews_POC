# Large Language Models (LLM) Analysis Tool

During the past year, LLMs have paved an impressive path. Their innate capability to comprehend over **six million forms** of communication has given rise to diverse applications. However, structured outputs can be elusive, especially when dealing with extensive data input. The good news? Models like **gpt-3.5-turbo** from OpenAI are adept at rendering their results in JSON, offering a structured output when combined with the right prompting and scripting.

## About This Repository

This repository introduces a straightforward app designed to **analyze Google Maps Reviews**. The underlying logic is versatile, making it extendable for analyzing different types of texts. Here's how it works:

1. **Input**: Feed the app with a series of reviews or other textual documents and the categories for analysis.
2. **Categorization**: The app assesses each document based on user-defined categories like:
   - Friendliness of staff
   - Quality of delivery
   - Speed of service
   ... and so on.
   
3. **Output**: For each review and category, the app produces:
   - A **written evaluation** (limited to 50 characters in English, customizable)
   - A **score** ranging from 1 (very negative) to 5 (very positive).

## Multilingual Magic

The beauty of LLMs is their multilingual prowess. Whether it's the data, the categories, or the requested evaluation, this tool can operate in virtually any language. It leverages the LLM's multilingual abilities to provide evaluations across a wide spectrum of languages.
