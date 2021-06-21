## Face Mask Detection using pretrained VGG19 


The notebook requires a kaggle environment with the following 3 datasets added in the _/inputs/_ directory
1. [Face Mask Detection](https://www.kaggle.com/andrewmvd/face-mask-detection)
2. [Face Mask Detection ~12K Images Dataset](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset)
3. [Haarcascades](https://www.kaggle.com/lalitharajesh/haarcascades)

Just create a new Kaggle notebook and click on _Add Data_ in the top right corner. Also set the accelerator to be the GPU. Training becomes much faster that way.

From here onwards, just run all the cells using a GPU accelerator and wait for 5-6 minutes for the model to be trained and evaluated.

### Demo Link
[Link to Youtube Demo]()

### Future Work
The saved model could be deployed onto a webpage and/or IoT hardware. Since it performs face detection AND mask detection, it can perform as a "security camera" to detect COVID violations.
Dystopian I know...

References
- [This notebook] by Nagesh Singh(https://www.kaggle.com/nageshsingh/mask-and-social-distancing-detection-using-vgg19)
- [Keras Docs](https://keras.io/)
- [Haarcascades](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)
- [This](https://keras.io/guides/transfer_learning/) excellent guide on transfer learning
