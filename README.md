# EEG_Signal_Classification
EEG (Electroencephalogram) signal refers to the electrical activity recorded from the brain using electrodes placed on the scalp. It is a non-invasive method of measuring brain activity and is commonly used in various fields, including neuroscience, clinical research, and brain-computer interfaces. The EEG signal represents the collective electrical activity of millions of neurons in the brain. It is characterized by different frequency bands, such as delta, theta, alpha, beta, and gamma, each associated with specific brain states or cognitive processes. By analyzing the EEG signal, researchers can gain insights into brain activity patterns, identify abnormalities or abnormalities, study cognitive processes, and monitor brain health.

The dataset here is taken from [here](https://drive.google.com/file/d/1Ql5jRm-JDHNm46sfX68ahEXCUrVw7VFR/view)
This dataset is used for Emotion recognition. 15 Chinese film clips (positive, neutral and negative emotions) were chosen from the pool of materials as stimuli used in the experiments. The selection criteria for film clips are as follows: (a) the length of the whole experiment should not be too long in case it will make subjects fatigue; (b) the videos should be understood without explanation; and (c) the videos should elicit a single desired target emotion. The duration of each film clip is about 4 minutes. Each film clip is well edited to create coherent emotion eliciting and maximize emotional meanings.

There are totally 15 trials for each experiment. There is a 15s hint before each clips and 10s feedback after each clip. The order of presentation is arranged so that two film clips targeting the same emotion are not shown consecutively. For the feedback, participants are told to report their emotional reactions to each film clip by completing the questionnaire immediately after watching each clip.

A new effective EEG feature named differential entropy is proposed to represent the characteristics associated with emotional states.

In the "data" folder, there are train and test dataset containing downsampled, preprocessed and segmented versions of the EEG differential entropy data.


The dataset containing extracted differential entropy (DE) features of the EEG signals. These data is well-suited to those who want to quickly test a classification method without propcessing the raw EEG data. The training set contains a total of 84420 data and testing set contains 58128 data. Each piece of data contains 310 values representing the data of 62 electrodes on 5 frequencies.


