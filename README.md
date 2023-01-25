# OCR_pasport

OCR –CNN (Deep learning exercise)

This project is OCR algorithm without using any OCR libraries or services. 
The model for recognition is made by superposition of several convolutional neural networks and one linear layer on the Pytorch framework. 
To train and validate the model, a synthetic dataset was generated script in generator.ipynb. 
The dataset consists of pictures with a resolution 360 x 32 and Cyrillic characters. 
You can also download the generated training data from here : 
https://disk.yandex.ru/d/jjwbV0qY2fbgwQ

The generated text taken from Russian News Corpus package which can be downloaded from here: 
https://github.com/maxoodf/russian_news_corpus.
