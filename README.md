# Weather Images Deep Learning
This deep learning project trains AI models to classify road surface conditions (e.g., clear, light snow, medium snow, plowed) using roadside images and weather data. It tackles real-world problems in winter road monitoring with a custom dataset collected from public sources and weather APIs.

LoadWeatherImages.ipynb:
Loads and preprocesses a dataset of road images and pairs them with historical weather data using image filenames and location-based API queries. Prepares training-ready data by resizing images, normalizing features, and structuring labels for classification.

Alternate_Method.ipynb:
Implements a custom ResNet-based deep learning model for road condition classification. Uses image and weather data, applies data augmentation, and trains the model with the Adam optimizer and learning rate scheduling to improve generalization and performance.


