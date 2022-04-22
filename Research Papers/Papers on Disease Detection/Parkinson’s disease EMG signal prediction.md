## LINK : https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8914553

# Topic : Parkinson’s disease EMG signal prediction using Neural Networks

## Summary of Research paper: 
1)	We propose proposes a comparison between different neural network models, using multilayer perceptron (MLPs) and recurrent neural network (RNN) models, for predicting
Parkinson’s disease electromyography (EMG) signals, to anticipate resulting resting tremor patterns.
2)	Functional electrical stimulation (FES) has been proposed by many authors as a potential method for reducing and controlling the pathological tremor. However, the feasibility and accuracy of FES depend heavily on the estimation of amplitude and frequency of the involuntary tremor signals, and the side-effect of FES on patient’s voluntary movements.
3)	In this work, we propose to evaluate and compare different neural network architectures, using MLPs, LSTM, and combined models to predict PD’s sEMG signals. Our  primary target is to be able to successfully predict a full window of the tremor pattern (approximately 0.2s) so that we can use it later for FES control optimization.
4)	Convectional WVG Graphs are sensitive to noise and requires high computational powers since it is complex.
5)	Two parameters that are targeted for getting more accuracy in the WVG Graph and these two Parameters are:
a.	Penetrable Distance 
b.	Scale Factor
5)	There data sets of EMG signals of Several Persons are taken for the classification and these three data sets are of persons:
a.	Healthy Person
b.	Suffering from Myopathy 
c.	Suffering from ALS 
6)	Using Graph Theory based features we saw that Discriminating capabilities between three classes increases significantly with the increase in values of parameters – Penetrable Distance and Scale Factor.
7)	Three binary (healthy vs. myopathy, myopathy vs. ALS and healthy vs. ALS) and one multiclass problems (healthy vs. myopathy vs. ALS) have been addressed in this  study and for each problem, we obtained optimum parameter values determined on the basis of F-value computed using one way analysis of variance (ANOVA) test. Using optimal parameter values, we obtained mean accuracy of 98.57%, 98.09% and 99.45%, respectively for three binary and 99.05% for the multi-class classification problem. Additionally, the computational time was reduced by 96% with optimally selected WVG parameters compared to traditional WVG.

Why this research:
1)	EMG is used for diagnostics of various NueroMuscular Diseases by Doctors:
a.	Myopathy
b.	Amyotrophic Lateral Sclerosis
2)	EMG Signal Analysis by Doctors is Time Consuming and Sometimes also inaccurate.
3)	

