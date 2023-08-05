# Emotion_Detection

Explore how to overcome overfitting without changing model architecture.

Steps Taken

- Prepare Configuration for the model used.
- Loading data into data loaders.
- Visualize Data.
- Exploring data (Unbalanced Data)
- Augment Data (Rotation, Flipping, Contrast).
- Add Resize and rescale as a layer in the model so if deployed in production you don't have to preprocess the images yourself the model can do it directly.
- Using LENET Architecture (2 Conv, 2 Dense).
- Handle unbalance in data through class weighting which basically means giving higher weight to class with fewer samples so the model is not biased.
- Training the model.
- Detect overfitting through validation data accuracy compared to train data accuracy.
- Try dropout for overfitting put value 0.2.
- Notice improvement.
- Try L2 regularization and put the value 0.0001.
- More training and noticing results. acc [0.9327214956283569, 0.7124670743942261, 0.8902546167373657].
- Evaluation and represents results.
- Plot Confusion matrix Notice class happy comes with the best results regarding TT.
