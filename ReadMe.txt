a.URL / Source for Dataset

 The Div2k data sets are collected from the following sources:

 https://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip
 https://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_HR.zip

b.
 Software Requirements:

  1.Google Colab Notebook
  2.Visual Studio Code
  3.Python
  4.PyTorch Framework

 Hardware Requirements:

  1.4GB RAM
  2.Windows 10 OS

c.Detailed Instructions to execute the Source Code

   1. Load the model: 
        The pre trained model is loaded

   2. Call encode function for encoding:
        The cover image and the secret message to be encoded are obtained as inputs from the user.The encode method is called which passes the inputs to the encoder network.The output steganography image gets created in the specified location.

   3. Call decode function for decoding:
        The steganography image is passed to the decode method which passes the input to the decoder network and the secret message is decoded from the image.
 

