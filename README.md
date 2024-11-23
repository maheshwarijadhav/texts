TEXT SUMMARISATION 


This project focuses on building and evaluating AI-based text summarization models. Our goal was to develop a solution capable of effectively condensing text while retaining essential information. To achieve this, we implemented three models: an encoder-decoder without attention, an encoder-decoder with attention, and a transformer model.

The encoder-decoder models use a traditional sequence-to-sequence architecture, where one model applies attention for focusing on specific text segments, while the other omits this mechanism. Meanwhile, the transformer model employs a self-attention mechanism, known for efficiently capturing long-range dependencies, offering a robust alternative in natural language processing tasks. During evaluation, both the transformer and encoder-decoder without attention models showed similar high accuracy, outperforming the encoder-decoder with attention model, which had the lowest accuracy among the three.

To make our solution more accessible, we deployed it on Streamlit, allowing for easy testing and interaction with our summarization models. Our work sheds light on the impact of attention mechanisms in summarization tasks and emphasizes the efficacy of transformers in text-based applications. This project, developed with the guidance of Prof. Diptee Ghusse and Sharmila Kharat, offers valuable insights into designing and deploying text summarization models, with potential applications in various information-intensive domains.
