# Network-Intrusion-Detection-System
With the enormous growth of computer networks usage and the huge increase in the number of applications running on top of it is increasing day by day.
Therefore, the role of Intrusion Detection Systems (IDSs), as special-purpose devices to detect anomalies and attacks in the network, is becoming more important. 
Our task to build network intrusion detection system to detect anomalies and attacks in the network. There are two problems:
Binomial Classification: Activity is normal or attack
Multinomial classification: Activity is normal or DOS or PROBE or R2L or U2R 
The attack classes are:
1) DOS: denial-of-service
2) R2L: unauthorized access from a remote machine, e.g. guessing password
3) U2R: unauthorized access to local superuser (root) privileges, e.g., various “buffer overflow” attacks
4) Probing: surveillance and another probing, e.g., port scanning

The dataset used was NSL-KDD dataset and Machine Learning Models used were NAÏVE BAYES, DESCISION TREE, LOGISTIC REGRESSION and SUPPORT VECTOR MACHINE (SVM)

The steps we will follow are:
1) LOADING THE DATASET
2) DATA PRE-PROCESSING
3) SPLITING THE DATA INTO TRAIN & TEST
4) TRAINING THE MODEL & GETTING THE ACCURACY
5) COMPARING THE ACCURACY

The detection efficiency was calculated using the above Machine Learning models out of which SVM was found out to be the most efficient in detecting the anomalies and attacks in the network followed by Logistic Regression, Decision Tree and  Naïve Baye’s.
