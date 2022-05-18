# CryptoCurrency Forecast

The following project consists of an analysis of data from three different cryptocurrencies (Bitcoin, XRP and Ethereum), to detect price fluctuations and their possible reasons, followed by the creation of an HMM (Hidden Markov Model) algorithm which, by taking into consideration the trend of the prices per minute of the last two years, we are able to get a prediction of the future trend of behavior of said currencies.

## Installation

In addition to the use of jupyter notebook, it will be necessary to install some libraries that can be installed using the following command on a jupyter cell 

```bash
!python -m pip install --user pyspark
!python -m pip install --user tqdm
!python -m pip install --user matplotlib
!python -m pip install --user pyArrow
!python -m pip install --user sklearn
!python -m pip install --user seaborn
!python -m pip install --user hmmlearn
!python -m pip install --user itertools
!python -m pip install --user json
```
