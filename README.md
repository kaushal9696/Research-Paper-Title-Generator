
# Research Paper Title Generator

Here I have used the transformer model for the title generation of the research paper while looking at the abstract of the research paper. I am comparing different pre-trained transformers and checking the quality of the prediction.



## Appendix

- Text to Title Generator
- Title to Text Generator




## Approach

- Scrap the research paper abstract from web.
- Use the api arxivscraper for scrapping the abstract of research paper along with title
- Tokenize
- Load Pre-trained Model
- Hyper-parameter tuning
- Generate and Load dataset
- Predict the outcome

## Model from HuggingFace
- Bert to Bert
- T5
- GPT2
## Installation

Install Requirments

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook

```bash
jupyter notebook
```
    
## Screenshots

![Screenshot0](https://github.com/kaushal9696/Research-Paper-Title-Generator/blob/main/Text2Title0.png)

![Screenshot1](https://github.com/kaushal9696/Research-Paper-Title-Generator/blob/main/Text2Title1.png)

![Screenshot2](https://github.com/kaushal9696/Research-Paper-Title-Generator/blob/main/Text2Title2.png)

