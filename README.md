
# Development-of-an-SVM-based-facial-recognition-model
The goal of this project is to build a face recognition system based on the SVM classifier. For this, we have after preparation of the database, done some pre-processing like face detection, face cropping, feature extraction using gradient oriented histograms and then SVM classification.

To do this, we have processeded by a few steps like data preparation, face detection and cropping, features extraction and SVM classification.

- Data preparation:  In this step, we have downloaded a data set who called "Cross-Age Celebrity Dataset” (CACD2000) containing 163446 images and we only take about 5000 images for our needs.

- Face detection and cropping: this step was the difficult step and the important one because we have a lot of techniques for detection but all of them don't perform and we want to have a face without noise. And also after detection, face are some noise like some pixels wich aren't important for us so we have to crop face detected.

- Feature extraction: In this project, the goal is to use HOG for feature extraction because it is the best for this and studies prove that.

- SVM classification: the last step is to build model based on SVM multi-classification. SVM is known like one of the best algorithm for multi-classification and gives good results and it's very simple and more accurate.
