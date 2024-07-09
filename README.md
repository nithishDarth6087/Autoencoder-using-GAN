To identify and defend networks against attacks such as Distributed Denial of Service (DDoS), Probe assaults, Remote-to-Local (R2L), and User-to-Root (U2R), the Intrusion Detection System (IDS), we used autoencoders and machine learning algorithms. 
We applied label encoding on the NSL KDD-99 dataset. 
To address class imbalances, many autoencoder models are used along with the generation of synthetic data via a Conditional Tabular Generative Adversarial Network (CTGAN). 
To extract ensemble features, autoencoder models like SNDAE, SAE, and SSDAE are coupled. 
Prior to training, dimensionality reduction is implemented. 
The collected characteristics are concatenated and utilized to train various classifiers (Random Forest, KNN, and SVM-OVO). 
A testing dataset is used to evaluate the trained model. 
A comparison is made between the classifiers and the ensemble model output.
