# Voice-Gender-Detection-SVM

### Link to dataset - https://drive.google.com/drive/folders/1Z9KiN5Zkh3Z9cxhNXVOWN0sPtwkwezgk?usp=sharing

**Introduction**

This project focuses on the task of voice gender detection using the VoxCeleb dataset — a 
large-scale collection of speech samples. The dataset features recordings from over 6,000 speakers, 
encompassing 3,683 male and 2,310 female individuals. It represents a broad spectrum of 
ethnicities, accents, and speaking styles, making it highly suitable for building models that can 
generalize well across diverse populations. 

To effectively analyze the raw audio data, a pre-processing pipeline is employed to extract 
meaningful features that capture the essential characteristics of human speech. The primary feature 
extraction method used is the computation of Mel-Frequency Cepstral Coefficients (MFCCs), 
which are widely recognized for their ability to model the human auditory perception system and 
are highly effective in speech-related machine learning tasks. 

Following feature extraction, a Support Vector Machine (SVM) with a linear kernel is 
trained to classify the gender of a speaker based on the extracted MFCC features. SVMs are chosen 
due to their strong performance in high-dimensional spaces and their ability to create robust 
decision boundaries between classes. 

The primary goal of this project is to build a gender classification model that is not only 
accurate but also computationally efficient. Beyond achieving high performance, the project aims 
to highlight the measurable and systematic differences in voice patterns between male and female 
speakers, providing insights into how gender-related characteristics manifest in speech signals. 

**Objectives**

• To analyze the effectiveness of voice-based features (e.g., MFCCs) in distinguishing 
gender. \
• To extract key acoustic features that capture vocal characteristics unique to each gender. \
• To train the SVM with a linear kernel for binary classification: Male vs. Female. \
• To evaluate model performance using metrics such as accuracy, precision, recall, and F1
score.
