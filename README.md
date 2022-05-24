# Digitization_of_ECG
A Python-based utility that converts ECG images into ECG signals, thereby digitising them.
There is a lot of ECG image data floating about; if we could digitise them all, we'd have a huge amount of digital data that could be readily analysed or put into robots to make predictions. A digitising method would also allow some AI approaches to predict ECG anomalies just by giving in an image of the ECG. The technology will first digitise the image before predicting the abnormality using a machine learning model.
The digitization process involves two parallel processes, grid digitization and signal digitization. The detection involves converting a color image of a cropped ECG lead to a binary image such that only pixels of interest are True.
