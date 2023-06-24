# Nerf_optic_sheath_diameter_measurement

![B](https://github.com/Abdennacer-Badaoui/Nerf_optic_sheath_diameter_measurement/assets/106801897/5be4cb41-5f7e-466c-bae0-628b22f8cf60)


## Abstract : 
 This project focused on ultrasound image segmentation
of the optic nerve sheath for measuring its diameter. The initial dataset consisted
of 15 images, each accompanied by corresponding labels in the form of masks.
The goal was to develop a model capable of accurately detecting these masks.
Several methods were explored, starting with feature extraction using the VGG
Model, followed by clustering algorithms. However, these approaches did not
yield satisfactory results. Consequently, image processing techniques were incorporated prior to feature extraction and clustering algorithms, but their accuracy
remained suboptimal.
To address the limitations, the project employed the Unet model, which
was trained on the available dataset. Since the dataset was limited, the initial
results were not highly accurate. To improve performance, data augmentation
techniques such as flipping and rotating were applied, resulting in enhanced
outcomes. Furthermore, transfer learning was utilized by training the encoder
part of the Unet model on a large dataset for breast cancer detection, while
the decoder parts were trained using the initial dataset. This transfer learning
approach yielded even better results.
To further enhance the model’s performance, an additional large dataset
specific to optic nerve sheath images was incorporated, again employing transfer
learning. This final step resulted in the best overall results achieved throughout
the project. The primary challenges encountered during the project were primarily attributed to the limited availability of data, which adversely affected the
performance of the models.

## Dataset
The dataset for this project consisted of several types of images, with the
main ones being the original ultrasound images of the optic nerve (1,2,3). There
were a total of 15 of these images, and each image had a corresponding clustered
image where segmentation was done manually (4,5,6). These clustered images
served as our labels for training the deep learning model. 

![Capture d’écran 2023-06-24 225823](https://github.com/Abdennacer-Badaoui/Nerf_optic_sheath_diameter_measurement/assets/106801897/a6c528c6-f95c-4f7e-ba7e-472e8ad35c07)


Additionally, for each
original image, there were 5 corresponding images that represent the different
masks that we needed to predict (7,8,9).


![Capture d’écran 2023-06-24 225905](https://github.com/Abdennacer-Badaoui/Nerf_optic_sheath_diameter_measurement/assets/106801897/ddbbd770-3be5-4c1d-bd05-3c2377367c4b)



## Questions ?
Any Questions? Don't hesitate to reach us: abdennacer.badaoui@student-cs.fr , hatim.mrabet@student-cs.fr .
