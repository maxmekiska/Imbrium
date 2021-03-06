# Imbrium


## Pip install

```shell
pip install imbrium
```

Standard and Hybrid Deep Learning Multivariate-Multi-Step & Univariate-Multi-Step
Time Series Forecasting.


                      ██╗███╗░░░███╗██████╗░██████╗░██╗██╗░░░██╗███╗░░░███╗
                      ██║████╗░████║██╔══██╗██╔══██╗██║██║░░░██║████╗░████║
                      ██║██╔████╔██║██████╦╝██████╔╝██║██║░░░██║██╔████╔██║
                      ██║██║╚██╔╝██║██╔══██╗██╔══██╗██║██║░░░██║██║╚██╔╝██║
                      ██║██║░╚═╝░██║██████╦╝██║░░██║██║╚██████╔╝██║░╚═╝░██║
                      ╚═╝╚═╝░░░░░╚═╝╚═════╝░╚═╝░░╚═╝╚═╝░╚═════╝░╚═╝░░░░░╚═╝


## Try Imbrium

Please ignore all cudart dlerror/warnings, since no GPU is setup in this jupyter binder environment:

[![badge](https://img.shields.io/badge/launch-Imbrium-E66581.svg?logo=data:image/png;base64,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)](https://mybinder.org/v2/gh/maxmekiska/Imbrium/main?labpath=TestImbrium.ipynb)

## Current Dependencies

Current dependencies are not listed in the requierements.txt as this file is used by the jupyter binder to run a demo of the newest imbrium version. Please find in the below the current dependencies.

```txt
python== 3.7.*
```

```txt
tensorflow==2.9.1
scikit-learn==0.21.3
matplotlib==3.5.2
numpy==1.21.6
pandas==0.25.1
```

## Basics

This library aims to ease the application of deep learning models for time
series forecasting. Multiple architectures are offered with a fixed
number of layers however the user has full control over the number of neurons
per layer, activation function type, loss function type, optimizer type and
metrics applied.
The library differentiates between two
modes:

1. Univariate-Multistep forecasting
2. Multivariate-Multistep forecasting

These two main modes are further divided based on the complexity of the underlying model architectures:

1. Standard
2. Hybrid

Standard supports the following architectures:

- Multilayer perceptron (MLP)
- Recurrent neural network (RNN)
- Long short-term memory (LSTM)
- Gated recurrent unit (GRU)
- Convolutional neural network (CNN)
- Bidirectional recurrent neural network (BI-RNN)
- Bidirectional long-short term memory (BI-LSTM)
- Bidirectional gated recurrent unit (BI-GRU)
- Encoder-Decoder recurrent neural network
- Encoder-Decoder long-short term memory
- Encoder-Decoder convolutional neural network (Encoding via CNN, Decoding via GRU)
- Encoder-Decoder gated recurrent unit

Hybrid supports:

- Convolutional neural network + recurrent neural network (CNN-RNN)
- Convolutional neural network + Long short-term memory (CNN-LSTM)
- Convolutional neural network + Gated recurrent unit (CNN-GRU)
- Convolutional neural network + Bidirectional recurrent neural network (CNN-BI-RNN)
- Convolutional neural network + Bidirectional long-short term memory (CNN-BI-LSTM)
- Convolutional neural network + Bidirectional gated recurrent unit (CNN-BI-GRU)

Please note that each model is supported by a prior input data pre-processing procedure which allows to set a look-back period, look-forward period, sub-sequences division (only for hybrid architectures) and data scaling method.

The following scikit-learn scaling procedures are supported:

- StandardScaler
- MinMaxScaler
- MaxAbsScaler
- Normalizing ([0, 1])
- None (raw data input)

During training/fitting, callback conditions can be defined to guard against
overfitting.

Trained models can furthermore be saved or loaded if the user wishes to do so.

## How to use Imbrium?

Simplified workflows, more possible.

### Univariate Models:

1. Univariate-Multistep forecasting - Standard architectures

```python3
from imbrium.predictors.univarstandard import BasicMultStepUniVar

predictor = BasicMultStepUniVar(steps_past: int,
                                steps_future: int,
                                data = pd.DataFrame(),
                                scale: str = '')

# Choose between one of the architectures:

predictor.create_mlp(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (50, 'relu'),
                                          'layer1': (25,'relu'),
                                          'layer2': (25, 'relu')})

predictor.create_rnn(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (40, 'relu'),
                                           'layer1': (50,'relu'),
                                           'layer2': (50, 'relu')})

predictor.create_lstm(optimizer: str = 'adam',
                      loss: str = 'mean_squared_error',
                      metrics: str = 'mean_squared_error',
                      layer_config: dict = {'layer0': (40, 'relu'),
                                            'layer1': (50,'relu'),
                                            'layer2': (50, 'relu')})

predictor.create_gru(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (40, 'relu'),
                                           'layer1': (50,'relu'),
                                           'layer2': (50, 'relu')})

predictor.create_cnn(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (64, 1, 'relu'),
                                           'layer1': (32, 1, 'relu'),
                                           'layer2': (2),
                                           'layer3': (50, 'relu')})

predictor.create_birnn(optimizer: str = 'adam',
                       loss: str = 'mean_squared_error',
                       metrics: str = 'mean_squared_error',
                       layer_config: dict = {'layer0': (50, 'relu'),
                                             'layer1': (50, 'relu')})

predictor.create_bilstm(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config: dict = {'layer0': (50, 'relu'),
                                              'layer1': (50, 'relu')})

predictor.create_bigru(optimizer: str = 'adam',
                       loss: str = 'mean_squared_error',
                       metrics: str = 'mean_squared_error',
                       layer_config: dict = {'layer0': (50, 'relu'),
                                             'layer1': (50, 'relu')})

predictor.create_encdec_rnn(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (100, 'relu'),
                                                  'layer1': (50, 'relu'),
                                                  'layer2': (50, 'relu'),
                                                  'layer3': (100, 'relu')})

predictor.create_encdec_lstm(optimizer: str = 'adam',
                             loss: str = 'mean_squared_error',
                             metrics: str = 'mean_squared_error',
                             layer_config: dict = {'layer0': (100, 'relu'),
                                                   'layer1': (50, 'relu'),
                                                   'layer2': (50, 'relu'),
                                                   'layer3': (100, 'relu')})

predictor.create_encdec_cnn(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (64, 1, 'relu'),
                                                  'layer1': (32, 1, 'relu'),
                                                  'layer2': (2),
                                                  'layer3': (50, 'relu'),
                                                  'layer4': (100, 'relu')})

predictor.create_encdec_gru(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (100, 'relu'),
                                                  'layer1': (50, 'relu'),
                                                  'layer2': (50, 'relu'),
                                                  'layer3': (100, 'relu')})

# Fit the predictor object - more callback settings at: https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping
predictor.fit_model(epochs: int,
                    show_progress: int = 1,
                    validation_split: float = 0.20,
                    batch_size: int = 10,
                    monitor='loss',
                    patience=3)

# Have a look at the model performance
predictor.show_performance()

# Make a prediction based on new unseen data
predictor.predict(data: array)

# Safe your model:
predictor.save_model()

# Load a model:
# Step 1: initialize a new predictor object with same characteristics as model to load
# Step 2: Do not pass in any data
# Step 3: Invoke the method load_model()
# optional Step 4: Use the setter method set_model_id(name: str) to give model a name

loading_predictor = BasicMultStepUniVar(steps_past: int, steps_future: int)
loading_predictor.load_model(location: str)
loading_predictor.set_model_id(name: str)
```

2. Univariate-Multistep forecasting - Hybrid architectures

```python3
from imbrium.predictors.univarhybrid import HybridMultStepUniVar

predictor = HybridMultStepUniVar(sub_seq: int, steps_past: int, steps_future: int, data = pd.DataFrame(), scale: str = '')

# Choose between one of the architectures:

predictor.create_cnnrnn(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config = {'layer0': (64, 1, 'relu'),
                                        'layer1': (32, 1, 'relu'),
                                        'layer2': (2),
                                        'layer3': (50, 'relu'),
                                        'layer4': (25, 'relu')})

predictor.create_cnnlstm(optimizer: str = 'adam',
                         loss: str = 'mean_squared_error',
                         metrics: str = 'mean_squared_error',
                         layer_config = {'layer0': (64, 1, 'relu'),
                                         'layer1': (32, 1, 'relu'),
                                         'layer2': (2),
                                         'layer3': (50, 'relu'),
                                         'layer4': (25, 'relu')})

predictor.create_cnngru(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config = {'layer0': (64, 1, 'relu'),
                                        'layer1': (32, 1, 'relu'),
                                        'layer2': (2),
                                        'layer3': (50, 'relu'),
                                        'layer4': (25, 'relu')})

predictor.create_cnnbirnn(optimizer: str = 'adam',
                          loss: str = 'mean_squared_error',
                          metrics: str = 'mean_squared_error',
                          layer_config = {'layer0': (64, 1, 'relu'),
                                          'layer1': (32, 1, 'relu'),
                                          'layer2': (2),
                                          'layer3': (50, 'relu'),
                                          'layer4': (25, 'relu')})

predictor.create_cnnbilstm(optimizer: str = 'adam',
                           loss: str = 'mean_squared_error',
                           metrics: str = 'mean_squared_error',
                           layer_config = {'layer0': (64, 1, 'relu'),
                                           'layer1': (32, 1, 'relu'),
                                           'layer2': (2),
                                           'layer3': (50, 'relu'),
                                           'layer4': (25, 'relu')})

predictor.create_cnnbigru(optimizer: str = 'adam',
                          loss: str = 'mean_squared_error',
                          metrics: str = 'mean_squared_error',
                          layer_config = {'layer0': (64, 1, 'relu'),
                                          'layer1': (32, 1, 'relu'),
                                          'layer2': (2),
                                          'layer3': (50, 'relu'),
                                          'layer4': (25, 'relu')})

# Fit the predictor object - more callback settings at: https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping
predictor.fit_model(epochs: int,
                    show_progress: int = 1,
                    validation_split: float = 0.20,
                    batch_size: int = 10,
                    monitor='loss',
                    patience=3)

# Have a look at the model performance
predictor.show_performance()

# Make a prediction based on new unseen data
predictor.predict(data: array)

# Safe your model:
predictor.save_model()

# Load a model:
# Step 1: initialize a new predictor object with same characteristics as model to load
# Step 2: Do not pass in any data
# Step 3: Invoke the method load_model()
# optional Step 4: Use the setter method set_model_id(name: str) to give model a name

loading_predictor =  HybridMultStepUniVar(sub_seq: int, steps_past: int, steps_future: int)
loading_predictor.load_model(location: str)
loading_predictor.set_model_id(name: str)
```

### Multivariate Models:

1. Multivariate-Multistep forecasting - Standard architectures

```python3
from imbrium.predictors.multivarstandard import BasicMultStepMultVar

# please make sure that the target feature is the first variable in the feature list
predictor = BasicMultStepMultVar(steps_past: int,
                                 steps_future: int,
                                 data = pd.DataFrame(),
                                 features = [],
                                 scale: str = '')

# Choose between one of the architectures:

predictor.create_mlp(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (50, 'relu'),
                                           'layer1': (25,'relu'),
                                           'layer2': (25, 'relu')})

predictor.create_rnn(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (40, 'relu'),
                                           'layer1': (50,'relu'),
                                           'layer2': (50, 'relu')})

predictor.create_lstm(optimizer: str = 'adam',
                      loss: str = 'mean_squared_error',
                      metrics: str = 'mean_squared_error',
                      layer_config: dict = {'layer0': (40, 'relu'),
                                            'layer1': (50,'relu'),
                                            'layer2': (50, 'relu')})

predictor.create_gru(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (40, 'relu'),
                                           'layer1': (50,'relu'),
                                           'layer2': (50, 'relu')})

predictor.create_cnn(optimizer: str = 'adam',
                     loss: str = 'mean_squared_error',
                     metrics: str = 'mean_squared_error',
                     layer_config: dict = {'layer0': (64, 1, 'relu'),
                                           'layer1': (32, 1, 'relu'),
                                           'layer2': (2),
                                           'layer3': (50, 'relu')})

predictor.create_birnn(optimizer: str = 'adam',
                       loss: str = 'mean_squared_error',
                       metrics: str = 'mean_squared_error',
                       layer_config: dict = {'layer0': (50, 'relu'),
                                             'layer1': (50, 'relu')})

predictor.create_bilstm(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config: dict = {'layer0': (50, 'relu'),
                                              'layer1': (50, 'relu')})

predictor.create_bigru(optimizer: str = 'adam',
                       loss: str = 'mean_squared_error',
                       metrics: str = 'mean_squared_error',
                       layer_config: dict = {'layer0': (50, 'relu'),
                                             'layer1': (50, 'relu')})

predictor.create_encdec_rnn(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (100, 'relu'),
                                                  'layer1': (50, 'relu'),
                                                  'layer2': (50, 'relu'),
                                                  'layer3': (100, 'relu')})

predictor.create_encdec_lstm(optimizer: str = 'adam',
                             loss: str = 'mean_squared_error',
                             metrics: str = 'mean_squared_error',
                             layer_config: dict = {'layer0': (100, 'relu'),
                                                   'layer1': (50, 'relu'),
                                                   'layer2': (50, 'relu'),
                                                   'layer3': (100, 'relu')})

predictor.create_encdec_cnn(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (64, 1, 'relu'),
                                                  'layer1': (32, 1, 'relu'),
                                                  'layer2': (2),
                                                  'layer3': (50, 'relu'),
                                                  'layer4': (100, 'relu')})

predictor.create_encdec_gru(optimizer: str = 'adam',
                            loss: str = 'mean_squared_error',
                            metrics: str = 'mean_squared_error',
                            layer_config: dict = {'layer0': (100, 'relu'),
                                                  'layer1': (50, 'relu'),
                                                  'layer2': (50, 'relu'),
                                                  'layer3': (100, 'relu')})

# Fit the predictor object - more callback settings at: https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping
predictor.fit_model(epochs: int,
                    show_progress: int = 1,
                    validation_split: float = 0.20,
                    batch_size: int = 10,
                    monitor='loss',
                    patience=3)

# Have a look at the model performance
predictor.show_performance()

# Make a prediction based on new unseen data
predictor.predict(data: array)

# Safe your model:
predictor.save_model()

# Load a model:
# Step 1: initialize a new predictor object with same characteristics as model to load
# Step 2: Do not pass in any data
# Step 3: Invoke the method load_model()
# optional Step 4: Use the setter method set_model_id(name: str) to give model a name

loading_predictor = BasicMultStepMultVar(steps_past: int, steps_future: int)
loading_predictor.load_model(location: str)
loading_predictor.set_model_id(name: str)
```
2. Multivariate-Multistep forecasting - Hybrid architectures

```python3
from imbrium.predictors.multivarhybrid import HybridMultStepMultVar

# please make sure that the target feature is the first variable in the feature list
predictor = HybridMultStepMultVar(sub_seq: int, steps_past: int, steps_future: int, data = pd.DataFrame(), features:list = [], scale: str = '')

# Choose between one of the architectures:

predictor.create_cnnrnn(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config = {'layer0': (64, 1, 'relu'),
                                        'layer1': (32, 1, 'relu'),
                                        'layer2': (2),
                                        'layer3': (50, 'relu'),
                                        'layer4': (25, 'relu')})

predictor.create_cnnlstm(optimizer: str = 'adam',
                         loss: str = 'mean_squared_error',
                         metrics: str = 'mean_squared_error',
                         layer_config = {'layer0': (64, 1, 'relu'),
                                         'layer1': (32, 1, 'relu'),
                                         'layer2': (2),
                                         'layer3': (50, 'relu'),
                                         'layer4': (25, 'relu')})

predictor.create_cnngru(optimizer: str = 'adam',
                        loss: str = 'mean_squared_error',
                        metrics: str = 'mean_squared_error',
                        layer_config = {'layer0': (64, 1, 'relu'),
                                        'layer1': (32, 1, 'relu'),
                                        'layer2': (2),
                                        'layer3': (50, 'relu'),
                                        'layer4': (25, 'relu')})

predictor.create_cnnbirnn(optimizer: str = 'adam',
                          loss: str = 'mean_squared_error',
                          metrics: str = 'mean_squared_error',
                          layer_config = {'layer0': (64, 1, 'relu'),
                                          'layer1': (32, 1, 'relu'),
                                          'layer2': (2),
                                          'layer3': (50, 'relu'),
                                          'layer4': (25, 'relu')})

predictor.create_cnnbilstm(optimizer: str = 'adam',
                           loss: str = 'mean_squared_error',
                           metrics: str = 'mean_squared_error',
                           layer_config = {'layer0': (64, 1, 'relu'),
                                           'layer1': (32, 1, 'relu'),
                                           'layer2': (2),
                                           'layer3': (50, 'relu'),
                                           'layer4': (25, 'relu')})

predictor.create_cnnbigru(optimizer: str = 'adam',
                          loss: str = 'mean_squared_error',
                          metrics: str = 'mean_squared_error',
                          layer_config = {'layer0': (64, 1, 'relu'),
                                          'layer1': (32, 1, 'relu'),
                                          'layer2': (2),
                                          'layer3': (50, 'relu'),
                                          'layer4': (25, 'relu')})

# Fit the predictor object - more callback settings at: https://www.tensorflow.org/api_docs/python/tf/keras/callbacks/EarlyStopping
predictor.fit_model(epochs: int,
                    show_progress: int = 1,
                    validation_split: float = 0.20,
                    batch_size: int = 10,
                    monitor='loss',
                    patience=3)

# Have a look at the model performance
predictor.show_performance()

# Make a prediction based on new unseen data
predictor.predict(data: array)

# Safe your model:
predictor.save_model()

# Load a model:
# Step 1: initialize a new predictor object with same characteristics as model to load
# Step 2: Do not pass in any data
# Step 3: Invoke the method load_model()
# optional Step 4: Use the setter method set_model_id(name: str) to give model a name

loading_predictor =  HybridMultStepMultVar(sub_seq: int, steps_past: int, steps_future: int)
loading_predictor.load_model(location: str)
loading_predictor.set_model_id(name: str)
```
## References
Brwonlee, J., 2016. Display deep learning model training history in keras [Online]. Available from:
https://machinelearningmastery.com/display-deep-
learning-model-training-history-in-keras/.

Brwonlee, J., 2018a. How to develop convolutional neural network models for time series forecasting [Online]. Available from:
https://machinelearningmastery.com/how-to-develop-convolutional-
neural-network-models-for-time-series-forecasting/.

Brwonlee, J., 2018b. How to develop lstm models for time series forecasting [Online]. Available from:
https://machinelearningmastery.com/how-to-develop-
lstm-models-for-time-series-forecasting/.

Brwonlee, J., 2018c. How to develop multilayer perceptron models for time series forecasting [Online]. Available from:
https://machinelearningmastery.com/how-to-develop-multilayer-
perceptron-models-for-time-series-forecasting/.
