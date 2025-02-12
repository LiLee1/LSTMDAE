# 202012使用了LSTM去噪自编码器，紧凑型的模型，更利于部署
可以作为方案（1）在设计compact紧凑型模型的时候降低了复杂度，也可以作为方案（3）降噪算法？方案（4）提高了识别准确率

# Real-Time Radio Technology and Modulation Classification via an LSTM Auto-Encoder

Identification of the type of communication technology and/or modulation scheme based on detected radio signal are challenging problems encountered in a variety of applications including spectrum allocation and radio interference mitigation. They are rendered difficult due to a growing number of emitter types and varied effects of real-world channels upon the radio signal. Existing spectrum monitoring techniques are capable of acquiring massive amounts of radio and real-time spectrum data using compact sensors deployed in a variety of settings. However, state-of-the-art methods that use such data to classify emitter types and detect communication schemes struggle to achieve required levels of accuracy at a computational efficiency that would allow their implementation on low-cost computational platforms. In this paper, we present a learning framework based on an LSTM denoising auto-encoder designed to automatically extract stable and robust features from noisy radio signals, and infer modulation or technology type using the learned features. The algorithm utilizes a compact neural network architecture readily implemented on a low-cost computational platform while exceeding state-of-the-art accuracy. Results on realistic synthetic as well as over-the-air radio data demonstrate that the proposed framework reliably and efficiently classifies received radio signals, often demonstrating superior performance compared to state-of-the-art methods.

Software requirement:
-----------------
1. Python 3.6 or higher (https://www.python.org/)
2. Tensorflow package (Initial experiment uses version 1.14) (https://www.tensorflow.org/)
