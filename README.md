# Zindi---GeoAI-Challege-Location-Mention-Recognition-BiLSTM-CRF-solution
Zindi 2nd place solution of the GeoAI Named Entity Recognition Challenge

# GeoAI-Challege-Location-Mention-Recognition-BiLSTM-CRF-solution

__Submitted by:__ Nabarup Maity(nabarupmaity@gmail.com)<br>
__Challenge link:__ https://zindi.africa/competitions/geoai-challege-location-mention-recognition-from-social-media

Kindly refer the notebooks for detailed solution I have tried to make it easy readable. 


__Data standards:__<br>
* For the given code it uses the train data for training model and validation data for model validation and test data for submission.(https://github.com/rsuwaileh/IDRISI/tree/main/LMR/data/EN/gold-random-json)
* As an external data I have used the pre-trained word vectors of glove twitter embedding with dimension of 100 that is of size <1 GB. Data is available at the following link (https://nlp.stanford.edu/projects/glove/)
* Packages: I have used the most recent version of python packages

__Dependencies:__<br>
* Spacy en_core_web_sm model(python -m spacy download en/ python -m spacy download en_core_web_sm)
* Jsonlines(!pip install jsonlines)
* plot_keras_history(!pip install plot_keras_history)
* tensorflow_addons(!pip install tensorflow_addons)



Happy learning !!
