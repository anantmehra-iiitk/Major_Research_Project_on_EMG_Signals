## LINK : https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8914553

# Topic : Parkinson’s disease EMG signal prediction using Neural Networks

## Summary of Research paper: 
1)	This paper propose proposes a comparison between different neural network models, using multilayer perceptron (MLPs) and recurrent neural network (RNN) models, for predicting
Parkinson’s disease electromyography (EMG) signals, to anticipate resulting resting tremor patterns.
2)	Functional electrical stimulation (FES) has been proposed by many authors as a potential method for reducing and controlling the pathological tremor. However, the feasibility and accuracy of FES depend heavily on the estimation of amplitude and frequency of the involuntary tremor signals, and the side-effect of FES on patient’s voluntary movements.
3)	In this paper, authors propose to evaluate and compare different neural network architectures, using MLPs, LSTM, and combined models to predict PD’s sEMG signals. Thier  primary target is to be able to successfully predict a full window of the tremor pattern (approximately 0.2s) so that we can use it later for FES control optimization.
4)	So for this study, Authors fixed the input window and predicted window sizes, by predicting the next 400 points based on the the last 4,000 points
5)	Proposed architectures:
a.	Multilayer perceptron (MLP)
b.	Multilayer LSTM 
c.	MLP Autoencoder
d.  LSTM Autoencoder
6)	For a relatively simple pattern like the EMG envelope, most models can predict with a good level of confidence. We can see that the best results are achieved with the decoder models after applying the MLP.
7)	As a result authors found out that both models, based on MLP and LSTM performed well for the EMG envelope. For the raw EMG, only the MLP decoder approach was able to
perform well with the encoded input from a previouslytrained MLP autoencoder.


