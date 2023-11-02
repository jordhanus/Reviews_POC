# 🌐 Large Language Models (LLM) Analysis Tool

During the past year, LLMs have left an indelible mark. Fluent in over six million forms of communication, they've unlocked a plethora of applications. 🚀 But when it comes to producing structured outputs, especially with massive data, the challenge persists. Good news? The **gpt-3.5-turbo** model from OpenAI shines at offering results in JSON, crafting structured outputs with adept prompting and scripting. 📊

## 💼 Business Value

Introducing a tool designed to **analyze Google Maps Reviews** 🌍. The potential for business with this app is profound:

- 🔍 **Deep Insights**: Dive into customer feedback pinpointing specific topics.
- 📈 **Competitive Analysis**: Don't just limit to your feedback, explore public reviews of competitors. Compare your services, staff efficiency, or even promotions against market leaders.
- 📡 **Real-Time Feedback**: Either dive into historical data or set up a live pipeline. Stay updated with real-time feedback, and get alerted to pivotal reviews instantly.

## 📝 About This Repository

The app is versatile, catering to various text analysis needs. Here's its modus operandi:

1. **Input** 📥: Pour in a collection of reviews or textual documents and specify categories for analysis.
2. **Categorization** 🏷️: The app reviews each document as per user-specified categories such as:
   - 🤝 Friendliness of staff
   - 🚚 Quality of delivery
   - ⚡ Speed of service
   ... and more.
   
3. **Output** 📤:
   - 📜 **Written Evaluation**: Concise feedback limited to 50 characters in English.
   - 🌟 **Score**: A rating between 1 (very negative) to 5 (very positive).
   - 📋 **Dataframe**: A fusion of the evaluation and score with the original data.
   - 🚧 *Work in Progress*: A business-centric dashboard, offering tailored insights.

## 🌍 Multilingual Magic

The prowess of LLMs lies in their linguistic versatility. No matter the language of the data, categories, or evaluations, this tool is up to the task. Harness the linguistic capabilities of LLMs and explore evaluations across numerous languages. 💬

# Exploring Alternatives

The recent OpenAI models are state of the art, but when run on a large scale, potentially quite expensive. Stay tuned for alternative solutions: firstly, of-the-shelves open source LLMs; and secondly and more promising, fine-tuned LLMs where a high-quality small-ish dataset is used to fine-tune a much larger foundation model to perform on par with (or even better than?) OpenAIs magic🪄
