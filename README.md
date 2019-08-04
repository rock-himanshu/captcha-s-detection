This project is done under Mr.Sahil Rajput(senior). He is a great leader and best mentor, I ever met.I also like to represent my gratitude for helping me and giving opportunity to work. This project really helped me to learn machine learning deep vision concept.

This project lead to new way of training a dataset using GAN technique which form a lookalike copy.

# CAPTCHA-Detection-using-Machine-Learning
I have designed a model using machine learning which can detect and break CAPTCHA.
<br>
This model is trained at 10,000 captcha image data set which is generated manually through GAN
( reference link: https://wordpress.org/plugins/really-simple-captcha/).<br>
After training this model, it is able to detect the captcha with accuracy of 99.98%.
<br>
# Motivation
Deep Learning for Computer Vision with Python by Adrian Rosebrock. (Found here: https://www.kickstarter.com/projects/adrianrosebrock/deep-learning-for-computer-vision-with-python-eboo) where the author showed how he bypassed the CAPTCHA on the New York website using machine learning.


# How to Run 

    $ python captcha_detection.py
It will:
1. Extract single letters from CAPTCHA images
2. The results will be stored in the "letter_images" folder.
3. The neural network will be train to recognize single letters and the result will write in “captcha_model.hdf5" and "model_labels.dat"

Now,
Run solve.py to solve CAPTCHA
      
    $ python solve.py
