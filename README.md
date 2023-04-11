# EEG-Reconstruction-With-a-Dual-Scale-CNN-LSTM-Model-for-Deep-Artifact-Removal
EEG artifact removal deep learning

this project provide the pulished paper and supplementary material document

Abstract—Artifact removal has been an open critical issue for decades in tasks centering on EEG analysis. Recent deep learning methods mark a leap forward from the
conventional signal processing routines; however, those in general still suffer from insufficient capabilities 1) to capture potential temporal dependencies embedded in EEG and 2) to adapt to scenarios without a priori knowledge of artifacts. This study proposes an approach (namely DuoCL) to deep artifact removal with a dual-scale CNN (Convolutional Neural Network)-LSTM (Long Short-Term Memory) model, operating on the raw EEG in three phases: 1) Morphological Feature Extraction, a dual-branch CNN utilizes convolution kernels of two different scales to learn morphological features (individual sample); 2) Feature Reinforcement, the dual-scale features are then reinforced with temporal dependencies (inter-sample) captured by LSTM; and 3) EEG Reconstruction, the resulting feature vectors are finally aggregated to reconstruct the artifact-free EEG via a terminal fully connected layer. Extensive experiments have been performed to compare DuoCL to six state-of-the-art counterparts (e.g., 1D-ResCNN and NovelCNN). DuoCL can reconstruct more accurate waveforms and achieve the highest SNR & correlation (CC) as well as the lowest error (RRMSEt & RRMSEf). In particular, DuoCL holds potentials in providing a high-quality removal of unknown and hybrid artifacts.

how to cite:
T. Gao, D. Chen, Y. Tang, Z. Ming and X. Li, "EEG Reconstruction With a Dual-Scale CNN-LSTM Model for Deep Artifact Removal," in IEEE Journal of Biomedical and Health Informatics, vol. 27, no. 3, pp. 1283-1294, March 2023, doi: 10.1109/JBHI.2022.3227320.
