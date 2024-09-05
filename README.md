# R2attention Unet for Semantic Segmentation

This repository implements the R2attention Unet model for semantic segmentation, with a unique training approach involving image patching and selective patch removal based on mask content. The approach has significantly improved accuracy compared to traditional methods.


## Training Approach 

We padded images to ensure divisibility by 224 (e.g., from 1024x1360 to 1024x1560) and implemented a strategy to remove patches with masks labeled only 0 during training. This focused the model on more informative regions, resulting in a notable accuracy improvement from 23% to 39%.

Contact

For questions or collaborations, feel free to reach out at suraj.prasad@iitb.ac.in.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Feel free to customize this template further based on additional details about your project or specific instructions you want to provide. Once you have filled in the specifics, you can save this content as your README.md file in your GitHub repository.


