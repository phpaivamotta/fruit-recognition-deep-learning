# :apple: :banana: Fruit Recognition Deep Learning Model :watermelon: :pear:

This project was completed as part of a university class at PUC-RIO University. The project was assigned as part of a class Bootcamp/Competition that lasted for a couple of months. My model placed second with an accuracy of approximately 93%.

The program was written on a Google Colab notebook and the model was trained on approximately 27,000 fruit images, which belonged to 13 different fruit categories:

:apple:, :banana:, :pear:, :pineapple:, :grapes:, :cherries:, :peach:, :lemon:, :coconut:, :mango:, :watermelon:, :orange:, :strawberry:

The model has 3 convolutional layers with 16, 32, and 64 filters respectively, each followed by a max pooling layer. A dropout layer with a rate of 0.5 is added after the fourth convolutional layer. The output of the fourth convolutional layer is flattened and fed into two dense layers with 128 and 13 units respectively. The activation functions used are ReLU and softmax.

Note: The image files could not be uploaded to this repo since their zipped size exceeded the 25MB limit. But the links to the Google Drive folders with the datasets can be accessed through the links below:

- Training dataset: https://drive.google.com/drive/folders/1RgzP1-N0cLV8n4He8d0Z3Uu14sMv4SlC?usp=share_link
- Testing dataset: https://drive.google.com/drive/folders/197smAmqi_Z4wH1XRkvolXFflzE0mxeBt?usp=share_link
