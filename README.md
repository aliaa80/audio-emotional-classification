# audio emotional classification
Classify a speech dataset by their emotions using some classification models

The dataset I used is:

https://github.com/pariajm/sharif-emotional-speech-dataset

and you can download audio files and json file from this repo.

I used many diffrent classification models such as SVC, RandomForest, Knn, DecisionTree and MLP and best result I got was for MLP that it's accuracy was 74%.

These are visualisation of MLP results:

![alt text](https://github.com/aliaa80/audio-emotional-classification/blob/main/result2.png?raw=true)


![alt text](https://github.com/aliaa80/audio-emotional-classification/blob/main/result1.png?raw=true)


Of course it's not a very good accuracy because this dataset isn't really balanced which you can see that number of labels aren't equal and there are huge difrencess between them

v2- After balancing data there was an huge progress in accuracies.Again I visualize MLP accuracy that is increased from 74 percent to 93 percent and confusion matrix below:


![alt text](https://github.com/aliaa80/audio-emotional-classification/blob/main/balanced_result2.png?raw=true)


![alt text](https://github.com/aliaa80/audio-emotional-classification/blob/main/balanced_result1.png?raw=true)
