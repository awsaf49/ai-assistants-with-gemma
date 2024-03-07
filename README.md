# Google – AI Assistants for Data Tasks with Gemma with [KerasNLP](https://github.com/keras-team/keras-nlp) and [Keras](https://github.com/keras-team/keras)

> The objective of this competition is to build tools to assist Kaggle developers.

<div align="center">
    <img src="https://i.ibb.co/8xZNc32/Gemma.png">
</div>

In this competition, we are asked to create notebooks that demonstrate how to use the Gemma LLM to accomplish one or more of the following developer-oriented tasks:
1. **<font color="red">Answer common questions about the Kaggle platform.</font>**
2. Explain or teach basic data science concepts.
3. Summarize Kaggle Solution write-ups.
4. Explain or teach concepts from Kaggle Solution write-ups.
5. Answer common questions about the Python programming language.

This notebook guides you through performing `"1. Answer common questions about the Kaggle platform"` task for the competition. As this task requires specific knowledge of Kaggle, we need precise information about Kaggle. To do so, I have created a dataset, ["Kaggle Docs"](https://www.kaggle.com/datasets/awsaf49/kaggle-docs), collecting data from [kaggle.com/docs](https://www.kaggle.com/docs/). To make things easier for the model, the data is curated to have Question-Answer pair format, but if you are interested, the raw data is also available. We will use this dataset to fine-tune **Gemma LLM** to answer questions about the Kaggle platform.

<u>Fun fact</u>: This notebook is backend-agnostic, supporting TensorFlow, PyTorch, and JAX. However, the best performance can be achieved from `JAX`. Utilizing KerasNLP and Keras allows us to choose our preferred backend. Explore more details on [Keras](https://keras.io/keras_3/).

**Note**: For a more in-depth understanding of KerasNLP, refer to the [KerasNLP guides](https://keras.io/keras_nlp/).
