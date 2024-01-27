### Dataset

In our study, we adopt the widely used Sleep-EDF database, and mainly dig into the SC part. It contains 153 PSG recordings belonging to 82 subjects. For 71 of them, the recording of the first night and the second night are available. As for each PSG recording, we mainly take four signals into consideration: 2 EEG(Fpz-CZ and Pz-Cz), 1 EOG (horizontal), and 1 EMG (submental chin). The EOG and EMG channels are sampled at 100Hz. Since full EMG recordings are not available, we only adopt 2 EEG and 1 EOG as input. Each 30-second epoch of the recordings was manually labelled by sleep experts according to the R&K standard [1]into one of eight categories {W, N1, N2, N3, N4, REM, MOVEMENT, UNKNOWN}. As this database has been used differently in literature, it should be stressed that only the in-bed parts (from lights off time to lights on time) of the recordings were used as recommended in [2],[3],[4].

[1] J. A. Hobson, “A manual of standardized terminology, techniques and
scoring system for sleep stages of human subjects,” Electroencephalography Clin. Neurophysiol., vol. 26, no. 6, 1969, Art. no. 644.

[2] H. Phan et al., “Joint classification and prediction CNN framework for
automatic sleep stage classification,” IEEE Trans Biomed Eng, vol. 66,
no. 5, pp. 1285–1296, 2019.

[3] O. Tsinalis et al., “Automatic sleep stage scoring with single-channel
EEG using convolutional neural networks,” arXiv:1610.01683, 2016.

[4]H. Phan et al., “DNN filter bank improves 1-max pooling CNN for
single-channel EEG automatic sleep stage classification,” in Proc.
EMBC, 2018, pp. 453–456.