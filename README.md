# Computer Vision Project: Movie Genre Prediction from Posters

### Task Overview
The goal of this project is to predict the genres of movies based on their posters. You will use a dataset of movie posters and their corresponding genres to train and evaluate machine learning models for this task.

### Dataset
1. **Movie Posters Dataset**: You can find a dataset of movie posters [here](https://www.kaggle.com/datasets/phiitm/movie-posters).
2. **Movie Metadata Dataset**: The dataset with metadata, including movie genres, is available [here](https://www.kaggle.com/code/phiitm/can-we-judge-a-movie-by-it-s-poster/notebook).

### Dataset Analysis
1. **Class Distribution**: Analyze the distribution of genres in the dataset to understand any class imbalance.
2. **Genre Co-occurrence**: Investigate how often movies have multiple genres, as movies usually belong to more than one genre.
3. **Data Visualization**: Visualize the composition of the dataset, including the distribution of genres and images.

### Image Preprocessing
1. **Image Quality Analysis**: Inspect the quality of the images in the dataset and decide on any necessary preprocessing steps.
2. **Data Augmentation**: Apply data augmentation techniques (e.g., rotation, flipping, scaling) to enhance model generalization.

### Models to Test
1. **Custom CNN Architecture**: Build and train your own CNN model for genre classification.
2. **ResNet**: Implement a ResNet model and fine-tune it for the task.
3. **ViT Classifier**: Use a Vision Transformer (ViT) for classification. You don’t need to train the ViT model itself, only the classification head.

### Results Analysis
1. **Performance Metrics**: Evaluate the models using appropriate metrics such as accuracy, precision, recall, and F1-score. Display these results with graphs.
2. **Error Analysis**: Visualize examples where the model makes mistakes to identify areas for improvement.
3. **Conclusions**: Summarize the findings, including the strengths and weaknesses of the models tested.
