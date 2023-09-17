# Hinglish to English Translation AI (T5-Small)
I built an English to Hinglish translator by fine-tuning T5-Small. The translated text sounds natural and converts all the difficult words and phrases in English to Hinglish. The translated text is easy to understand for even a non-native Hindi speaker.

# Model
T5, short for Text-to-Text Transfer Transformer, derives its foundation from the Transformer Architecture and undergoes training to tackle a wide array of NLP tasks. T5 operates within a text-to-text framework, where it approaches NLP challenges, such as translation, conversation, summarization, sentiment analysis, and more, as tasks revolving around converting one textual input into another textual output. In essence, T5 regards all these tasks as instances of transforming text from one form to another.

# Dataset
The dataset used was taken from hugging face. It can be found here (https://huggingface.co/datasets/findnitai/english-to-hinglish)

# Installing and Executing
The code can be taken from the hinglish.py file. It can be run on Google Colab, Jupyter as well as your local machine. All the libraries needed are already added in the Python file.

# Challenges faced and Solved
* The data widely available is not upto the mark, hence finetuning on the custom dataset resulted in the model to give highly accurate Hinglish translations 
  for English text
* For the conversion Llama-2 could also be used which would give better results, but here we have used T5-Small due to GPU restrictions.
* Hence, the Next step in this project would be to use the Llama-2 model to generate translations in the future.
