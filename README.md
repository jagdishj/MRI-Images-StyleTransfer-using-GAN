# MRI-Images-StyleTransfer-using-GAN

There are various types of MRI that have the ability to capture different types of abnormalities. However, one type of MRI may not be sufficient in capturing a particular type of abnormality. In this case, having another type of MRI may enhance the accuracy of a diagnosis, thus leading to better treatment of the patient.

However, gaining access to different imaging techniques is difficult and expensive. Also, doctors often prescribe one type of MRI at once, but what if you could create another type of MRI from the one that we already have? Moreover, without investing the same amount of time and money?

Generative adversarial networks (GANs) provide the luxury of creating another type of MRI from the existing one. In this capstone, you will use a particular variant of GANs, called CycleGAN, to translate the style of one MRI image into another. This will help in gaining a better understanding and analysis of the scanned image. By using GANs, we will create T2 weighted images from T1 weighted MRI images and vice-versa.

Type	T1 Highlight Style	T2 Highlight Style
Water	Dark	Very Bright
Fat	Very Bright	Dark
Bone	Dark	Dark
Muscle	Intermediate	Dark
Tumours	Intermediate	Bright

T1 and T2 type MRIs in concrete terms. There are some component types such as Water, Fat, Muscle and Tumors which establish contrast relationship between MRIs. Moreover some of the elements have different contrast level whereas Bone component in MRIs gets highlighted in the same way in both the MRIs. Hence we can see that it’s a partial contrast but not complete contrast. As this is not a complete list of components that are highlighted in the MRIs

