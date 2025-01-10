# Neutral-Style-Transfer
Apply the artistic style of one image (style image) to another (content image) while preserving the structure of content image. This work uses VGG network 
Using the VGG network.

**Training**
1. **Feature Extraction**: Pass the content and style images throught the VGG to extract their respective features.
2. **Loss function**:
 * Content loss: The difference between the content features of the generated image and the content image
 *  Style loss: Difference in the Gram matrices of the style features of the generated image and the style image. 
3. **Update step** Minimized the combined loss function to iteratively update the pixels of the generated image 
 

