# cvbot

Welcome to cvbot! 

Collect Computer Vision (CV) approaches and apply them.

# Update 06 June 2020 

*Image inpainting with OpenCV and Python*

Credit to: https://www.pyimagesearch.com/2020/05/18/image-inpainting-with-opencv-and-python/

Require input:
* Source Images: image that we aim to inpaint and restore 
* Masks: mask image (Unfortunately, you need to manually generate it.)

Algorithm 
* https://www.researchgate.net/publication/238183352_An_Image_Inpainting_Technique_Based_on_the_Fast_Marching_Method
* https://www.math.ucla.edu/~bertozzi/papers/cvpr01.pdf

File 
* Put source images and masks images under folder cvbot/data
    * Source images: impainting_image.jpeg
    * Masks images: impainting_mask.jpeg
        * You can create it by built-in image editor in Mac. 
            * Draw black rectangle to mask the target position 
            * Tune image contrast to min and exposure to max.