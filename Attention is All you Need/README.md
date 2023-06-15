# Attention Is All You Need

This notebook is a direct implementation of [Attention Is All You Need](https://arxiv.org/abs/1706.03762).

**Comments on Computation Resources:**
* Reduce the batch size of DataLoader according to your computational resources. 
* If you face any effects similar to browser crash/dead kernel, you need to upgrade your computation resources.
* Though I haven't distributed the processes across GPUs, please do that for better resource management.
  
Project Setup:
```bash
conda env create -f environment.yml
python -m spacy download de_core_news_sm
python -m spacy download en_core_web_sm
conda activate transformer
```

**Resource/References:**
* Code related to Word Embeddings has been taken from [here](http://nlp.seas.harvard.edu/annotated-transformer/).