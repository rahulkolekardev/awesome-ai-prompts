
# Awesome AI Prompts 🚀

[![Dataset on Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-datasets-blue)](https://huggingface.co/datasets/syntheticbot/awesome-ai-prompts)
[![GitHub Repo stars](https://img.shields.io/github/stars/rahulkolekardev/awesome-ai-prompts?style=social)](https://github.com/rahulkolekardev/awesome-ai-prompt)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated collection of 100 high-quality, detailed, and safe-for-work prompts designed to unlock the full potential of modern Large Language Models (LLMs).

This dataset moves beyond simple questions and commands, providing structured scenarios that instruct an AI to adopt a specific persona (`act`) and perform a complex task (`prompt`). It's an ideal resource for prompt engineers, researchers, educators, and anyone looking to have more creative and productive interactions with AI.

You can download and explore the dataset directly on the [Hugging Face Hub](https://huggingface.co/datasets/syntheticbot/awesome-ai-prompts).

## ✨ Why This Dataset?

*   **High-Quality & Detailed:** Each prompt is crafted to be a comprehensive instruction set, challenging models to generate nuanced, detailed, and context-aware responses.
*   **Safe & Broadly Applicable:** Fully SFW and curated for a wide range of professional, scientific, educational, and creative applications.
*   **Role-Playing Focus:** The `act` and `prompt` structure is perfect for testing a model's ability to adopt and maintain a persona.
*   **LLM Agnostic:** Designed to be effective across all major language models, helping you compare their strengths and capabilities.

## 🤖 Compatibility with Major LLMs

These prompts are designed to work effectively with a wide range of state-of-the-art language models. The detailed nature of the prompts allows each model to showcase its unique strengths.

*   **OpenAI (ChatGPT, GPT-4, GPT-4o)**
    *   **Strengths:** Excellent at following complex, multi-part instructions and maintaining a consistent persona throughout a long response. The detailed scenarios in this dataset play well to GPT-4's robust reasoning capabilities.

*   **Google (Gemini Pro, Gemini 1.5)**
    *   **Strengths:** Gemini's large context window and strong multi-modal reasoning make it adept at handling prompts that require synthesizing information or adopting a role that involves explaining complex topics.

*   **Anthropic (Claude 3 Sonnet, Opus)**
    *   **Strengths:** Claude models often excel at creative writing, nuanced dialogue, and adopting a specific tone or "voice." They perform exceptionally well on prompts requiring literary flair, ethical reasoning, or empathetic role-playing.

*   **Open-Source Models (Llama 3, Mixtral, etc.)**
    *   **Strengths:** This dataset is an invaluable resource for the open-source community. It can be used as a high-quality evaluation set to benchmark instruction following and role-playing capabilities or as a basis for fine-tuning models to improve their performance on complex, professional tasks.

## 🎯 Use Cases

*   **🎓 Educational Resource:** A fantastic tool for exercises in critical thinking, problem-solving, and creative writing across many subjects.
*   **⚙️ Fine-tuning LLMs:** Use this dataset to fine-tune instruction-following models to improve their ability to handle complex, professional-grade tasks.
*   **📊 Model Evaluation:** A great benchmark to compare how different LLMs perform on nuanced, persona-driven instructions.
*   **💡 Prompt Engineering:** A source of inspiration for crafting better, more detailed prompts for any application.

## 📂 Dataset Structure

The dataset is simple and consists of two columns:

*   **`act`**: A `string` describing the persona or expert role the AI should adopt.
*   **`prompt`**: A `string` containing the detailed instructions for the AI.

### Example

| act                                | prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A Business Strategy Simulator      | I want you to act as a business strategy consultant. I will provide a company, a market, and a specific challenge (e.g., 'a legacy bookstore facing online competition', 'a new software startup trying to enter a crowded market'). You will develop a comprehensive business strategy. This should include marketing plans, product development suggestions, financial considerations, and a competitive analysis. Your first case is 'a local coffee shop competing with a new Starbucks opening next door'. |

## 🚀 Getting Started

You can download the dataset directly from the [Hugging Face Hub](https://huggingface.co/datasets/syntheticbot/awesome-ai-prompts) or browse the files in this repository.

To use the prompts, simply choose a row from the dataset and combine the `act` and `prompt` to form your request to the language model.

### Example Usage with an LLM

**Your Input:**
> I want you to act as a **Business Strategy Simulator**.
>
> **Prompt:** I want you to act as a business strategy consultant. I will provide a company, a market, and a specific challenge (e.g., 'a legacy bookstore facing online competition', 'a new software startup trying to enter a crowded market'). You will develop a comprehensive business strategy. This should include marketing plans, product development suggestions, financial considerations, and a competitive analysis. Your first case is 'a local coffee shop competing with a new Starbucks opening next door'.

## 🤝 Contribution

This dataset is currently static, but we are open to community contributions in the future. If you have ideas for high-quality prompts, feel free to open an issue to discuss them.

## 📜 License

This dataset is licensed under the [MIT License](./LICENSE). You are free to use, modify, and distribute it.

## ✍️ Citation

If you use this dataset in your research, projects, or articles, please consider citing it:

```
@misc{awesome-ai-prompts-2024,
  author = {Rahul Kolekar and AI Contributors},
  title = {Awesome AI Prompts: A Curated Dataset for Advanced LLM Instruction},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/rahulkolekardev/awesome-ai-prompts}}
}
```
