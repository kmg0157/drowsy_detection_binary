# drowsy_detection_binary

This project is to classify images into drowsiness and normal condition.

The ones used for image preprocessing are haar cascade and mediapipe.

WideResnet tried to create a more accurate classification model by expanding the range of models.

### Environment & Package
1. NVIDIA Titan XP (CUDA 10.2)
2. Python 3.8.10
3. Tensorflow-gpu 2.10.0
4. Mediapipe 0.9.0.1
5. Keras 2.10.0

### Result

Check the code for the detailed structure of the model.

1. Model 1 (CNN)
   
![image](https://github.com/kmg0157/drowsy_detection_binary/assets/102772772/d61ab8ba-6d22-4197-b020-563e92b4c62f)

2. Model 2 (WideResnet+ReLU)

![image](https://github.com/kmg0157/drowsy_detection_binary/assets/102772772/c7e5a23e-0a1d-4850-b1db-4da7c4ded29d)

3. Model 3 (WideResnet+Leaky ReLU)

![image](https://github.com/kmg0157/drowsy_detection_binary/assets/102772772/0fc945c0-6936-4f88-a1d0-00b0e317fa25)

### Test
![image](https://github.com/kmg0157/drowsy_detection_binary/assets/102772772/a290e083-2124-4273-bf3b-cae32fe86d5f)

The model with WideResnet did not achieve the desired level of learning results due to a lack of epochs.
