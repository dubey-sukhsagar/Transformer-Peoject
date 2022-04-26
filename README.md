# MLSP-Final-Peoject-
Thermal, electrical stress ,Decomposition of insulating ma-
terial and incipient faults leads to generation of various type
of gases (H2, CH4, C2H6, CO2 etc) inside oil filled trans-
formers. These abnormal operating condition are hard to
detect by normal mechanism.
So task is to classify the faults based on the Dissolve gas
concentration. I took 200 data points attached with paper
H. A. Illias and W. Zhao Liang(1) to train the model.I used
below model/algorithms in different combination to get best
generalised model with high accuracy

Sr.No.	Applied Models/Algo	(Accuracy on Test data) %
1	Raw data+SVM	50
2	Normalized data +SVM	95
3	Normalized data +SVM with PSO	96
4	Normalized data +SVM with MEPSO	97.83
5	Normalized reduced  data with step wise regression +SVM with PSO	90
6	Normalized reduced  data with LDA +SVM with PSO	94
![image](https://user-images.githubusercontent.com/26180953/165332043-2975ed27-0bf6-4a00-bdd4-a491233defa2.png)
