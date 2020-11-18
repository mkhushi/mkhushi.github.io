# mkhushi.github.io
Foreign Exchange (Forex) is the largest financial market in the world. The daily trading volume of the Forex market is much higher than that of stock and futures markets. Therefore, it is of great significance for investors to establish a foreign exchange forecast model. In this paper, we propose a Wavelet Denoised-ResNet with LightGBM model to predict the rate of change of Forex price after five time intervals to allow enough time to execute trades. All the prices are denoised by wavelet transform, and a matrix of 30 time intervals is formed by calculating technical indicators. Image features are obtained by feeding the maxtrix into a ResNet. Finally, the technical indicators and image features are fed to LightGBM. Our experiments on 5-minutes USDJPY demonstrate that the model outperforms baseline modles with MAE: 0.240977×10<sup>-3</sup> MSE: 0.156×10<sup>-6</sup> and RMSE: 0.395185×10<sup>-3</sup>. An accurate price prediction after 25 minutes in future provides a window of opportunity for hedge funds algorithm trading.

##There are three parts in the project##
1.DataProcessing is about how to deal with the dataset
2.Prediction is about the predict method for the forex change rate
3.Dataset is the USDJPY 5M dataset from 2004.1.1 to 2020.6.9

Instruction:
1.In the dataset there is a large USDJPY M5 dataset from 2004.1.1 to 2020.6.9,in the paper,I used the dataset from 2019.1.1 to 2020.6.9
2.Run the DataProcessing.py which include the wavelet denoise method and caculation of technical indicators to process the data
3.Run the prediction.ipynb block by block
4.If you want to modify the code,you can follow the comments in the ipynb
