# DeepLOB: Limit Order Book Prediction

This project reproduces **DeepLOB**, based on the paper *"DeepLOB: Deep Convolutional Neural Networks for Limit Order Books"* by Zhang et al. It combines **CNN, Inception and LSTM architectures** to extract spatial and temporal features from limit order book data and predict future mid-price movements.

Implemented in PyTorch on the **FI-2010 dataset**, the project evaluates predictions at multiple horizons and benchmarks DeepLOB against a multinomial logistic regression baseline. It also includes an execution-delay-aware trading simulator to evaluate the profitability and robustness of the generated signals.
