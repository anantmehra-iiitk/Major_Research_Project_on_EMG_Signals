## LINK : 

# Topic : Applied Soft Computing

## Summary of Research paper: 
1)	In this paper, the usefulness of the different feature extraction methods for describing MUP morphology is investigated, Also soft computing techniques were presented for the classiﬁcation of intramuscular EMG signals.
2)	The proposed method by the authors automatically classiﬁes the EMG signals into normal, neurogenic or myopathic.
3)	Also, multilayer perceptron neural networks (MLPNN), dynamic fuzzy neural network (DFNN) and adaptive neuro-fuzzy inference system (ANFIS) based classiﬁers were compared in relation to their accuracy in the classiﬁcation of EMG signals.
## Proposed Method-:
## Subjects and data acquisition-:
An EMG system with standard settings was used. The EMG signal was acquired from the biceps brachii muscle using a concentric needle electrode. The  recording points within the muscle are standardized, with MUPs recorded from three to ﬁve different needle insertions. MUPs were not recorded close to the surface of the muscle. The electrode was usually advanced at least 3–5 mm into the muscle before recording. The electrode was also moved at least 3–5 mm between recordings to make sure that different MUPs are recorded. The electrode was advanced until the medial or posterior border of the muscle is reached. The electrode was then pulled out and inserted to a new radial direction.

1.1.	Feature extraction method-:
The success of any signal classiﬁcation system depends on the choice of features used to characterize the raw signals. This paper used autoregressive (AR) method and the Wavelet Transform as a comparative work for feature extraction from the EMG.
1.1.1.	Autoregressive modelling of EMG signals
 Autoregressive (AR) method makes use of a linear process, com- monly referred to as a model to estimate the power spectrum. The model parameters adjusted for the best match between model out- put and the waveform of interest. When the best match is obtained, the model’s frequency characteristics give the best estimate of the waveform’s spectrum.
1.1.2.	Feature extraction using discrete wavelet transform
The Wavelet transform (WT) presents the time–frequency rep- resentation. WT is able to provide the time and frequency informa- tion at the same time, thus giving a time–frequency representation of the signal. As the time-domain signal is passed from various high pass and low pass ﬁlters, then, either portion or both are taken, and do the same thing again. This operation is called decomposition.
The following statistical features were utilized to represent the time–frequency distribution of the EMG signals: 

(1)	Mean of the absolute values of the coefﬁcients in each sub-band.
(2)	Average power of the wavelet coefﬁcients in each sub-band.
(3)	Standard deviation of the coefﬁcients in each sub-band.
(4)	Ratio of the absolute mean values of adjacent sub-bands.

Feature extraction using wavelet packed energy
Unlike wavelet transform which is realized only by a low-pass ﬁlter bank, wavelet packet transform (WPT) is realized by a two-channel ﬁlter bank which can be iterated over either a low-pass or a high-pass branch. Therefore, the information in high frequencies can be analysed as well as that in low frequencies in WPT. As a consequence, ﬁner frequency bands can be gained by WPT than by wavelet transform.
For Classification-:
Artiﬁcial neural networks (ANN)-:
A typical ANN has three layers: input; hidden; and output. This kind of network is known as a multi-layer perceptron neural net- work (MLPNN). Because of this complexity it is possible that the network can be practically tolerant of missing values.
The MLPNN was designed with combined features of EMG signal in the input layer; and the output layer consisted of three nodes representing normal, myopathic or neurogenic disorder.

1.1.3.	Dynamic fuzzy neural networks (DFNN)
Neuro-fuzzy systems are fuzzy systems that use ANNs theory in order to validate their properties by using data examples. In order to characterize inaccurate data and knowledge, fuzzy rules are used instead of exact rules when representing knowledge. The dynamic fuzzy neural network (DFNN)  is an implementation of the Takagi–Sugeno–Kang (TSK) fuzzy system based on an extended radial basis function networks (RBFN) and its learning algorithm
By using the DFNN algorithm several sets of fuzzy rules were extracted from the EMG data set. First, three fuzzy predicates were used to represent each of the input attributes and each of the three output variables. A DFNN structure was trained with fuzziﬁed EMG training data for 1500 training cycles, a learning rate of 0.1 and momentum of 0.2 until an RMS error of 0.01. Fuzzy rules were then extracted. Several experiments with test examples were carried out, which is the confusion matrix of the desired classiﬁcation and 
1.1.4.	The adaptive neuro-fuzzy inference systems (ANFIS)
The adaptive network-based fuzzy inference system (ANFIS) ﬁrst introduced by Jang in 1993 . ANFIS composed of three abstract components: a fuzzy rule base, which includes a set of fuzzy if–then rules; a database, which identiﬁes the membership functions used in the fuzzy rules; and a reasoning mechanism,
which carries out the inference procedure upon the rules to get a reasonable output or conclusion


## Result-:
The comparative analysis sug- gests that the ANFIS modelling is superior to the DFNN and MLPNN in at least three points: slightly higher recognition rate; insensitivity to overtraining; and consistent outputs demonstrating higher reliability.
