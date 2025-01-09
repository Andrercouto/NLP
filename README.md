# NLP

O objetivo deste repositório é consolidar e registrar meus conhecimentos em NLP.

Para inicializar novo ambiente e instalar bibliotecas:

```
conda create --name NLP python=3.11
conda activate NLP

conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
conda install -c conda-forge seaborn
conda install -c conda-forge numpy
conda install -c conda-forge scikit-learn
conda install -c conda-forge keras
conda install -c conda-forge tensorflow
conda install -c conda-forge nltk
conda install -c conda-forge spacy
conda install -c conda-forge textblob
conda install -c conda-forge transformers
conda install -c conda-forge torch torchvision torchaudio
conda install -c conda-forge ipywidgets
conda install -c conda-forge openai
conda install -c conda-forge BERTopic
conda install -c conda-forge sentence-transformers

python -m spacy download pt_core_news_lg
python -m spacy download en_core_web_lg 
```