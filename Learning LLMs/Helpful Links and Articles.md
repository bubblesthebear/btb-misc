# Helpful Links and Articles I found While Learning about LLMs
*Note:  This is not a comprehensive list, and only includes things I found during and after July 2024. The list is much larger, but spread across different devices, etc.*
*Note:  Summaries are generated by an LLM and may not be accurate for why the article is noteworthy. This is to save time for me. This is for quickly formatting personal notes and references. I don't really think anyone will see this.*

Title: The Illustrated Transformer
URL: https://jalammar.github.io/illustrated-transformer/
Summary:
This article explains the Transformer model, a deep learning architecture that uses self-attention mechanisms to process input sequences in parallel. The Transformer is composed of an encoder and a decoder, each with multiple identical layers. The encoder processes the input sequence and generates a continuous representation that is passed to the decoder. The decoder generates the output sequence, one element at a time, using the encoder's output and self-attention mechanisms.


Title: Mastering Large Language Models (LLMs)
URL: https://github.com/lehidalgo/mastering-llms
Summary:
This GitHub repository provides a comprehensive roadmap for mastering Large Language Models (LLMs). The roadmap is divided into sections, each focusing on a specific aspect of LLMs, and includes a list of resources for learning each topic, including books, online courses, and tutorials.

Key Points:
- The roadmap covers various aspects of LLMs, including NLP basics, transformer models, and advanced topics.
- The repository includes resources for learning NLP basics, such as books and tutorials.
- It provides a detailed guide for mastering LLMs, divided into sections for easy navigation.
- The resources listed include both theoretical and practical materials for a comprehensive understanding of LLMs.
- The roadmap is designed to help users embark on a journey to master LLMs.


Title: Imitation Intelligence, my keynote for PyCon US 2024
URL: https://simonwillison.net/2024/Jul/14/pycon/

Summary:
This article discusses the author's keynote speech at PyCon US 2024, focusing on Large Language Models (LLMs) and their capabilities. The author emphasizes that these models are not truly intelligent but rather imitate human-like behavior through statistical autocomplete. The speech covers various aspects of LLMs, including their construction, evaluation, and potential applications, as well as the challenges and security concerns associated with integrating them into other systems.

Key Points:
- **Imitation Intelligence**
  - The term "Artificial Intelligence" can be misleading.
  - "Imitation Intelligence" better describes Large Language Models.
- **Construction and Training**
  - LLMs are built using vast amounts of training data.
  - They are not unfathomably large, but rather a few terabytes in size.
- **Evaluation and "Vibes"**
  - Evaluating LLMs is difficult due to the subjective nature of their output.
  - The LMSYS Chatbot Arena helps evaluate models through user feedback.
- **Openly Licensed Models**
  - Models like LLaMA and Mistral are openly licensed, allowing for local use.
- **Prompt Engineering**
  - Building software around LLMs involves prompt engineering.
  - This includes techniques like Retrieval Augmented Generation.
- **Function Calling and Security**
  - LLMs can be integrated with other tools to enhance their capabilities.
  - However, this integration raises significant security concerns, such as prompt injection.
- **Personal Digital Assistants**
  - Building secure personal digital assistants is a challenging task.
  - The risk of prompt injection attacks must be carefully addressed.