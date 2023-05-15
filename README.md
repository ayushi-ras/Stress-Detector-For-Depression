# Stress-Detector-For-Depression

Voice stress analysis (VSA) is collectively a pseudoscientific technology that aims to infer deception from stress measured in the voice. The technology aims to differentiate between stressed and non-stressed outputs in response to stimuli (e.g., questions posed), with high stress seen as an indication of deception. In this work, we propose a deep learning-based psychological stress detection model using speech signals. With increasing demands for communication between humans and intelligent systems, automatic stress detection is becoming an interesting research topic. Stress can be reliably detected by measuring the level of specific hormones (e.g., cortisol), but this is not a convenient method for the detection of stress in human- machine interactions. The proposed algorithm first extracts Mel- filter bank coefficients using pre-processed speech data and then predicts the status of stress output using a binary decision criterion (i.e., stressed or unstressed) using CNN (Convolutional Neural Network) and dense fully connected layer networks




Mel-Frequency Cepstral Coefficients 

Computing filter banks and MFCCs involve somewhat the same procedure, where in both cases filter banks are computed and with a few more extra steps MFCCs can be obtained. In a nutshell, a signal goes through a pre-emphasis filter; then gets sliced into (overlapping) frames and a window function is applied to each frame; afterwards, we do a Fourier transform on each frame (or more specifically a Short-Time Fourier Transform) and calculate the power spectrum; and subsequently compute the filter banks. To obtain MFCCs, a Discrete Cosine Transform (DCT) is applied to the filter banks retaining a number of the resulting coefficients while the rest are discarded. A final step in both cases, is mean normalization.


 Run the project in the local development server 
 run the ipynb file in the jupyter notebook 
 
