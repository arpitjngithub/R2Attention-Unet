# R2Attention U-Net for Enhanced Semantic Segmentation
This repository features the implementation of the R2Attention U-Net model for semantic segmentation, employing an innovative training strategy that combines image patching with selective patch removal. This method has yielded significant accuracy gains compared to conventional techniques.

# Training Methodology
To optimize model performance, images were padded to dimensions divisible by 224 (e.g., from 1024x1360 to 1024x1560). During training, patches containing only mask label 0 were excluded, allowing the model to focus on more informative regions. This approach resulted in a substantial accuracy improvement, increasing from 23% to 39%.

# Contact Information
For inquiries or collaboration opportunities, please contact arpitjain8302@gmail.com
