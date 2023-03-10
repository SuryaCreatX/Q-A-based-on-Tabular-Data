# Q-A-based-on-Tabular-Data
Table Question Answering (Table QA) refers to providing precise answers from tables to answer a user's question. I aim to provide an overview of available datasets and representative methods in table QA. We classify existing methods for table QA into five categories according to their techniques, which include semantic-parsing-based, generative, extractive, matching-based, and retriever-reader-based methods. 

### Create conda env

```
conda create -n tqa Python=3.8
conda activate tqa
```

### Install Depencencies

```
pip install streamlit
pip install transformers
pip install torch torchvision torchaudio
pip install torch-scatter -f https://data.pyg.org/whl/torch-1.10.0+cpu.html

```

### To run the code

```
streamlit run app.py
```
