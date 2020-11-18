# mkhushi.github.io
Foreign Exchange (Forex) is the largest financial market in the world. The daily trading volume of the Forex market is much higher than that of stock and futures markets. Therefore, it is of great significance for investors to establish a foreign exchange forecast model. In this paper, we propose a Wavelet Denoised-ResNet with LightGBM model to predict the rate of change of Forex price after five time intervals to allow enough time to execute trades. All the prices are denoised by wavelet transform, and a matrix of 30 time intervals is formed by calculating technical indicators. Image features are obtained by feeding the maxtrix into a ResNet. Finally, the technical indicators and image features are fed to LightGBM. Our experiments on 5-minutes USDJPY demonstrate that the model outperforms baseline modles with MAE: 0.240977×10<sup>-3</sup> MSE: 0.156×10<sup>-6</sup> and RMSE: 0.395185×10<sup>-3</sup>. An accurate price prediction after 25 minutes in future provides a window of opportunity for hedge funds algorithm trading.

Here is the code

https://github.com/mkhushi/code-with-paper/tree/main/Forex%20Price%20Prediction%20by%20Wavelet%20Denoised-ResNet%20CNN%20and%20LightGBM

