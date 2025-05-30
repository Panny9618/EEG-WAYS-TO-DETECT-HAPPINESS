SJTU Emotion EEG Dataset for Four Emotions (SEED-IV)
This is a subset of SEED (SJTU Emotion EEG Dataset: http://bcmi.sjtu.edu.cn/~seed/) for emotion recognition

Label:
The labels of the three sessions for the same subjects are as follows,
session1_label = [1,2,3,0,2,0,0,1,0,1,2,1,1,1,2,3,2,2,3,3,0,3,0,3];
session2_label = [2,1,3,0,0,2,0,2,3,3,2,3,2,0,1,1,2,1,0,3,0,1,3,1];
session3_label = [1,2,2,1,3,3,3,1,1,2,1,0,2,3,3,0,2,3,0,0,2,0,1,0];

The labels with 0, 1, 2, and 3 denote the ground truth, neutral, sad, fear, and happy emotions, respectively.

The size of the sliding time windows for feature extraction is 4 seconds.

References:
If you use SEED-VIG in your research, please cite our following paper:
Wei-Long Zheng, Wei Liu, Yifei Lu, Bao-Liang Lu, and Andrzej Cichocki, EmotionMeter: A Multimodal Framework for Recognizing Human Emotions. IEEE Transactions on Cybernetics, 2018.

 https://panny9618.github.io/EEG-WAYS-TO-DETECT-HAPPINESS/
