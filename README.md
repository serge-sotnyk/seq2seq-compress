# Compress sentences using CNN with attention

This example was inspired by https://github.com/CVxTz/keras/blob/master/examples/cnn_seq2seq.py and database of compressed sentences from Google https://github.com/google-research-datasets/sentence-compression.git

# Instructions
- Install Keras, Tensorflow
- Unpack \*.json files from archive https://github.com/serge-sotnyk/seq2seq-compress/releases/download/corpus/sentence-compression.zip into directory "/data"
- To construct TSV input, run [make_clean_corpora.ipynb](make_clean_corpora.ipynb). This step is optional, because files comp-data.eval.tsv and sent-comp.train.tsv is already stored into this repo.
- To train model, run [cnn_seq2seq.ipynb](cnn_seq2seq.ipynb). This step is also optional, because trained model and network options are already stored in the repo, but you can retrain model with your own hyperparameters.
- To use pretrained model, run [use_pretrained_cnn_model.ipynb](use_pretrained_cnn_model.ipynb). To compress your own sentences, change contents of user_inputs variable.

