Steps taken:

- Find suitable dataset, found one on kaggle (linked in the notebook's `Overview` section)
- Start laying foundation for gathering the data and filtering it (faced difficulties with an exception, didn't release I need to pass `dtype=object` to `np.array()`)


# Model 1:
- Using deep learning with Visual Geometry Group (VGG-19) architecture
- 19 layers (16 convolutional, 3 fully conntected)
- VERY taxing on the hardware & slow

INITIAL RESULTS WHEN CREATING history_03:
- accuracy: 0.7386 - loss: 0.5746 - val_accuracy: 0.5000 - val_loss: 0.7298 - learning_rate: 1.0000e-04