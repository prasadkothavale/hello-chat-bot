# 👋 Hello Chat Bot
In this repository I have created some notebook to playaround with training and finetuning 🤗 Hugging Face models.

* [gpt2](https://github.com/prasadkothavale/hello-chat-bot/tree/main/gpt2): Train gpt2 model
* [rag](https://github.com/prasadkothavale/hello-chat-bot/blob/main/rag/langchange_investopedia.ipynb): Train a Retrieval Augmented Generation (RAG) model using scraped data from [investopedia](https://investopedia.com/)
* [utils/scrape_investopedia_dictionary](https://github.com/prasadkothavale/hello-chat-bot/blob/main/utils/scrape_investopedia_dictionary.ipynb) : Scraps [investopedia dictionary](https://www.investopedia.com/financial-term-dictionary-4769738) and stores each defination in a new text file.

### Setup
Following are the quick instructions to install required python libraries, however it is recommened to create an environment to isolate this setup

```sh
pip install tensorflow[and-cuda]
# pip install tensorflow # for cpu only
pip install datasets, transformers, torch, tqdm, tf-keras, transformers[torch], faiss-gpu
pip install jupyterlab, ipywidgets
```

### Execution
```sh
jupyter lab
```

