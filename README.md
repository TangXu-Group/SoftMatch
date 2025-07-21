# SoftMatch

This repository provides the code for the methods and experiments presented in our paper 'SoftMatch Distance: A Novel Distance for Weakly-Supervised Trend Change Detection in Bi-Temporal Images'. (Pattern Recognition)

![image](https://github.com/user-attachments/assets/5d5cb8df-ae2d-4b62-b943-48a1c39e7f44)

If you have any questions, you can send me an email. My mail address is yqunyang@163.com

Training
=
Prepare
---
The based dependencies of runing codes:
```
torchvision: 0.9.0
torch: 1.8.0
python: 3.8.17
```
Start
---
First, according to the experiemtal setting in the paper, the data and the corresponding trend and binary labels can be generated.
Then, use ```Train_test.ipynb``` to train and test the model.

Here, ```Train.txt```and```text.txt``` look like the following,
![image](https://github.com/TangXu-Group/SoftMatch/assets/74549002/ac3b45b1-0607-4ee7-9b62-731cb96e91f3)
