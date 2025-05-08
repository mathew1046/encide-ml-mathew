# encide-ml-mathew
# 🐾 Cats vs Dogs Classifier (Mini Dataset)

I built a binary image classifier using **MobileNetV2**, a pre-trained convolutional neural network, with transfer learning to classify cats and dogs using a small dataset of around 1,000 images (500 cats and 500 dogs). The dataset was organized into `Cat/` and `Dog/` folders under `data/`, and the model was trained in Google Colab. After preprocessing and data augmentation, the model was fine-tuned and achieved a validation accuracy of approximately **96%**. Predictions on a separate test set were saved in a CSV file with filenames and predicted labels.

To run the code:
1. Download the `.ipynb` notebook.
2. Upload your `kaggle.json` API key (available in your Kaggle account settings).
3. Upload the `test_images.zip` file (used for testing the model).
