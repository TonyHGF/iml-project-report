



### Introduction

_During sleep our brain goes through a series of changes between different sleep stages, which are characterized by specific brain and body activity patterns. Sleep stage classification, that is, dividing sleeping stages into N1, N2, N3, N4, REM and awake, is one of the fundamental technical investigations at the basis of clinical decision-making in sleep medicine diagnostics and treatment efficacy evaluation. Currently, the referenceable standard of sleep staging are overnight multiple electroencephalograms (EEG) and electrooculograms (EOG). This manual approach is, however, labor-intensive and time-consuming due to the need for EEG and EOG recordings from several sensors attached to subjects over several nights. Algorithmic sleep staging aims at automating this process, which can be a helper clinically._

Various systems have been founded during these years:

- In 2010, In [36], the author proposed feature weighting method using K-means clustering. Welch spectral transform was used for feature extraction, and the selected features were used with K-means and decision tree techniques. The study reported an overall accuracy of 83%.  
- In 2017, a combination of convolutional and recurrent layers was proposed by  [Supratak et al., 2017, Biswal et al., 2017].  

- Li et al. [5] combined random forests and rules developed from the R&K sleep manual achieving an accuracy of 0.86 and Cohen’s kappa (*κ*) of 0.805 on a dataset with 198 subjects from Cleveland Sleep Study.
-  Koley et al. [6] and Lajnef et al. [8] used similar expert-defined features to train a support vector machine. [6] achieved *κ* of 0.86 on 28 subjects from Center of Sleep Disorder Diagnosis, India and [8] achieved an accuracy of 0.88 on 15 subjects from DyCog Lab, France respectively. 
- 2017, DeepSleepNet CNN+LSTM
- 2023, CatBoost