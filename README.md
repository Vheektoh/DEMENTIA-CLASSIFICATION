# Dementia Classification Using MRI Imaging
This project focuses on the classification of dementia using MRI imaging data. The goal is to develop
a robust deep learning-based system for identifying and categorizing dementia cases to aid in early 
diagnosis and treatment planning.

## Dataset
The Open Access Series of Imaging Studies (OASIS) is a project dedicated to providing freely accessible
neuroimaging datasets to the scientific community, aiming to advance research in neuroscience and related fields.
https://www.kaggle.com/datasets/pulavendranselvaraj/oasis-dataset
This dataset contains 9488 brain MRI images categorized into four classes based on Alzheimer's progression.
Patient classification relied on provided metadata and Clinical Dementia Rating (CDR) values, yielding four 
classes: demented, very mild demented, mild demented, and non-demented. These classes facilitate the examination
of various stages of Alzheimer's disease progression.


## Methodology
Three Convolutional Neural Network (CNN) architectures were employed for this task:

- ResNet: A state-of-the-art deep residual network known for its efficiency in handling vanishing
  gradient issues in deep architectures.
- AlexNet: One of the pioneering CNN models that introduced key deep learning concepts.
- Custom CNN: A bespoke architecture tailored to the dataset's specific requirements.

## Results
- ResNet achieved the highest accuracy and emerged as the best-performing model due to its depth and
 ability to capture complex features in MRI images.
- AlexNet was the second-best model, demonstrating strong performance but slightly lower accuracy compared to ResNet.
- The custom CNN also delivered promising results but was outperformed by ResNet and AlexNet.

## Conclusion
ResNet's superior performance underscores its effectiveness in extracting detailed features from MRI images, 
making it an excellent choice for dementia classification tasks. 
