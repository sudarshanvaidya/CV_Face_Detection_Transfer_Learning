# CV_Face_Detection_Transfer_Learning

Using transfer learning of an object detector model to detect faces in a given image


Solution Approach:


1. Reuse MobileNet model.

2. Reuse functions for batch generation, loss function and bounding box utilities.

3. Use WIDER FACE dataset for training the model.

4. Explore image label information and load train and test data.

5. Initiate MobileNet model and freeze layers for transfer learning.

6. Load model weights.

7. Prepare training and validation batch generators.

8. Initilaize Hyper Parameters learning rate, epochs, optimizer and loss function.

9. Add early stopping and model checkpoint layers on validation loss with some patience values.

10. Train the model on data generated batch-by-batch.

11. Load the best saved model with best Validation accuracy.

12. Plot the bounding box in the test image to show the predictions.

13. Create a folder and get the predictions for the test images.

14. Visualize a test image to check predictions.

15. Try bounding box prediction with different values of confidence threshold.

16. Conclusions

