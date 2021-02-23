# [Style Transfer using CycleGan Medical Images](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/cyclegan_medical_GitHUB.ipynb)

## Radiologist misdiagnose 40 million people worldwide each and every single year🤯!

One of the complicated tasks in medical imaging is to diagnose MRI (Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.

But to have access to different imaging is difficult & expensive & this where, we can use the deep learning for synthetic image generaton to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

![](https://media2.giphy.com/media/l2Je9sD0VmZOmjJew/200.gif)


In the [dataset](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/dataset.zip "Data") we have 2 types of images, T1 weighted images and T2 weighted images.

**T1-weighted → fat issue appear to be bright**

**T2-weighted → both fat and water regions appear to be bright**

![](https://geekymedics.com/wp-content/uploads/2020/04/meningioma-770x331.png)
![](https://miro.medium.com/max/850/0*hkIDyRfNbZrr6W99.png)


having both type of MRI scans will enhance the accuracy of diagnosis.However, in practice, pathologists rarely have access to both types of MRI images for review and diagnosis purposes. This is because of a variety of reasons such as certain scan time limitations as well as other factors such as distorted contrast found in MRI images due to noise or artifacts.

[CycleGAN](https://arxiv.org/pdf/1703.10593.pdf) is used for style transfer and image generation. CycleGAN have its own advantages, like produces it high quality images and does not required paired data.

More on, project details are given in [Project Summary](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/CycleGAN%20summary.pdf "Summary"). Project code is given [here](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/cyclegan_medical_GitHUB.ipynb).Project outcomes are shown below:

## Training

![](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/Training.png "Training")

**Average Generator loss G at epoch 200: 0.81**

**Average Generator loss F at epoch 200: 0.77**

**Average Discriminator loss X at epoch 200: 0.69**

**Average Discriminator loss Y at epoch200: 0.67**


## Testing

![](https://github.com/jay-k2j2/Style-Transfer-using-CycleGan---Medical-Images/blob/main/Output.png)
