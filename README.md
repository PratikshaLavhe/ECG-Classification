# ECG-Classification
Project Description:-
ECG Classification and Arrhythmia Detection using CNN
Introduction:-
The electrocardiogram (ECG) has become a useful too for the diagnosis of cardiovascular diseases as it is fast and noninvasively. It has been reported that about 80% of sudden cardiac deaths are the result of ventricular arrhythmias or irregular heartbeats. While an experienced cardiologist can easily distinguish arrhythmias by visually referencing the morphological pattern of the ECG signals, a computer-oriented approach can effectively reduce the diagnostic time and would enable the e-home health monitoring of cardiovascular disease . However, realizing such computer-oriented approaches remains challenging due to the time-varying dynamics and various profiles of ECG signals, which cause the classification precision to vary from patient to patient , as even for a healthy person, the morphological pattern of their ECG signals can vary significantly over a short time
Electrocardiogram (ECG) is a record of electrical activities of the heart. It is usually of the form of a graph of voltage values versus time.  It is produced by using electrodes which are placed on the skin to detect electrical changes caused by depolarization and repolarization of cardiac muscle during each cardiac circle.
There are mainly three major deflections that record the sequence of electrical propagation • The P wave represents the depolarization of the atria. • The QRS complex represents the depolarization of the ventricles. • After a brief delay, repolarization of the ventricular cells is signalled by the T wave.
Abstract:-
Although convolutional neural networks (CNNs) can be used to classify electrocardiogram (ECG) beats in the diagnosis of cardiovascular disease, ECG signals are typically processed as one-dimensional signals while CNNs are better suited to multidimensional pattern or image recognition applications. In this study, the morphology and rhythm of heartbeats are fused into a two-dimensional information vector for subsequent processing by CNNs that include adaptive learning rate and biased dropout methods. The results demonstrate that the proposed CNN model is effective for detecting irregular heartbeats or arrhythmias via automatic feature extraction. 
Classification System:-
There are three major stages in a heartbeat classification system: pre-processing, feature extraction, and classification. In this study, preprocessing includes information fusion and one-hot encoding, while feature extraction is performed by the proposed CNNs. Finally, a common classifier called Softmax is used for classification, which solves multiple classification problems via logistic regression.


Diagram:-
 
 


Neural Network:-
Artificial neural networks are networks for simulation of learning process in human brains.
An application of an artificial neural network for machine reading of text, was one of the first widely known applications3, and many followed soon after. ... By applying algorithms that mimic the processes of real neurons, we can make the network 'learn' to solve many types of problems.





The human neuron system:-
 

Artificial Neuron System:-

 

Convolutional Neural Networks (CNN):-
 	Convolutional neural network (CNN) is one of the first successful architectures of deep learning. We use CNN for classification of images, video, texts, and speech. • Here, we will focus on the classification of ECG signals.
 • Layers in CNN
• Convolutional Layer 
• Pooling Layer 
• Activation Layer
Model for Classification:-
 

ECG Denoising:-
An ECG signal is a weak signal with an amplitude less than 100 mV in which the energy is concentrated in the 0.5–30 Hz frequency range [37]. Such weak signals are susceptible to corruption by environmental noise and other factors; thus, recorded ECG signals often include noise and interference, such as myoelectric interference, baseline drift, and power frequency interference. In Experiment 1, which is described later, the baseline drift was removed using a bandpass filter (passband: 0.1–100 Hz) [18] and the high-frequency noise was partially removed using a three-scale discrete wavelet transform, which removes the coefficients below a certain threshold [38, 39]. The Daubechies 5 (db5) wavelet basis function was adopted and the threshold was estimated via the Stein unbiased likelihood method. 
Plot for Accuracy and Loss of model:-
Accuracy and Validation Accuracy:-
Loss:-	
 






Prediction from the model and it’s Performance matrix:
	Performance Matrix (i.e. Confusion Matrix):-
 
Performance Matrix in Probabilistic Form:-
 
Conclusion:-
In this work, a CNN based classification system of ECG signals was proposed that included both the ADADELTA and biased dropout algorithms to improve performance. In the preprocessing stage, the 1D information fusion vector was transformed into a 2D image via one-hot encoding to improve the accuracy and convergence speed of classification. The results demonstrated that the ADADELTA optimizer significantly increased the learning rate and convergence speed.
References:-
1.	L. Lapidus, C. Bengtsson, B. Larsson, K. Pennert, E. Rybo, and L. Sjöström, “Distribution of adipose tissue and risk of cardiovascular disease and death: a 12 year follow up of participants in the population study of women in Gothenburg, Sweden,” British Medical Journal, vol. 289, no. 6454, pp. 1257–1261, 1984.View at: Publisher Site | Google Scholar
2.	J. J. Oresko, Z. Jin, J. Cheng et al., “A wearable smartphone-based platform for real-time cardiovascular disease detection via electrocardiogram processing,” IEEE Transactions on Information Technology in Biomedicine, vol. 14, no. 3, pp. 734–740, 2010.View at: Publisher Site | Google Scholar


