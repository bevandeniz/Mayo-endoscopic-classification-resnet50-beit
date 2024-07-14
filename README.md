# Mayo-endoscopic-classification

Medical diagnostics is a critical area that requires expert knowledge and high-technology imaging devices. Images such as endoscopy results give expert insights into the internal conditions of various human body organs. From the perspective of artificial intelligence, tasks such as image classification have been studied many times, and various models are also applied to medical diagnostics. There is a need for labeled datasets to use this model, which requires labeling by experts. An example of this dataset type is LIMUC (Labeled Images for Ulcerative Colitis) [1]. LIMUC dataset includes endoscopic images for four cases, with labels ranging from 0 to 3. While case 0 is the least harmful, case 3 is the most critical.

![image](https://github.com/user-attachments/assets/4275e85c-90df-48d3-8981-8f9285ff3c1e)

This project used ResNet50 and Bidirectional Encoder representation from Image Transformers (BEiT) models to classify the given image's condition from 0 to 3.
Confusion matrix and Quadratic Weighted Kappa (QWK) are evaluation metrics.


## References
[1] Polat, Gorkem, et al. "Improving the computer-aided estimation of ulcerative colitis severity according to mayo endoscopic score by using regression-based deep learning." Inflammatory Bowel Diseases 29.9 (2023): 1431-1439. Bao, H., Dong, L., Piao, S., & Wei, F. (2021). Beit: Bert pre-training of image transformers. arXiv preprint arXiv:2106.08254. 
