© Bütün haklar saklıdır.

Bu projenin tüm hakları saklıdır. Kodun, tasarımın ve içeriğin izinsiz olarak kopyalanması, dağıtılması, değiştirilmesi veya herhangi bir şekilde kullanılması yasaktır.
© 2025 mikbalyilmaz


****************************************************************************************************************************************


All rights reserved.

All rights to this project are reserved. The code, design, and content may not be copied, distributed, modified, or used in any way without permission.
© 2025 mikbalyilmaz


****************************************************************************************************************************************

ANN Fish Classificaiton and Prediction;
A deep learning model has been developed for the classification of fish species using image data. The goal is to create a robust and accurate model capable of effectively recognizing various types of fish from images. This project serves as a portfolio piece to demonstrate proficiency in machine learning (ML), image processing, and artificial neural networks (ANN). The project utilizes TensorFlow, a powerful open-source library for machine learning and deep learning, which provides a comprehensive ecosystem for building, training, and deploying ML models. TensorFlow is specifically used to construct the neural network architecture by leveraging the Keras API for creating layers, compiling the model, and fitting the model to the training data. NumPy, a fundamental package for scientific computing in Python, is utilized for handling and manipulating arrays, particularly for image data and labels. Pandas, a powerful data manipulation and analysis library, is used to read, process, and analyze the dataset containing image paths and corresponding labels. Matplotlib is employed for creating static, animated, and interactive visualizations, enabling the visualization of the training process and evaluation of model performance through accuracy and loss metric plots. Seaborn provides a high-level interface for drawing attractive statistical graphics and is used to create aesthetically pleasing visualizations, such as heatmaps for confusion matrices. Pillow (PIL) adds image processing capabilities to Python, facilitating the loading and processing of images for input into the model. Keras, as a high-level API for building and training deep learning models, simplifies the model creation process with pre-defined layers and structures. Scikit-learn provides tools for data mining and analysis, including various algorithms for classification, regression, and clustering, and is used for model evaluation metrics. Finally, ImageDataGenerator is employed for real-time data augmentation, enhancing the model's robustness by generating modified versions of images during training (credit to George Edward P. Box for this concept). The combination of these libraries and tools enables efficient handling, processing, analysis, and evaluation of image data within this project, showcasing the application of advanced ML techniques and demonstrating the development of practical, real-world applications in the field of computer vision.

Here are several important points to consider and highlight. First, the code only imports files with the .png extension. If your dataset contains images with different extensions (e.g., .jpg, .jpeg), these need to be taken into account; otherwise, these files will be ignored. Second, excluding directories named 'GT' ensures that only valid images are included. This step is crucial because the 'GT' directory typically stands for 'Ground Truth,' which may not be suitable for model training. Additionally, it is critical that each image's label is determined based on the directory name it resides in; incorrect labeling can lead to faulty learning by the model. Third, converting labels to the 'category' data type optimizes memory usage and enhances performance during analysis. However, it is important to ensure that this step is valid for all categories of data. Checking the distribution of labels in the dataset is also critical for observing class imbalance. If some labels are significantly fewer in number than others, this may negatively impact the model's performance. Fourth, recording the start time of the process is useful for performance evaluation. This measurement should consider not only the runtime of the code but also other parameters like memory usage and data loading time. Finally, displaying the first few rows of the DataFrame is helpful for checking the accuracy of labels; however, conducting a more comprehensive review and analyzing the entire dataset is a better approach to ensure the correctness of labels. 

Dataset, 
(6750, 2)
(2250, 2)
accuracy: 0.9897
Test set accuracy: 0.9933
------------------------------------------------------------------------------------------------------------------------------------------------------------------
myucanlar@gmail.com
https://github.com/mikbalyilmaz
www.linkedin.com/in/muhammed-ikbal-yilmaz-36622a276
