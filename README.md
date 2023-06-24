# Nerf_optic_sheath_diameter_measurement

![1](https://github.com/Abdennacer-Badaoui/Nerf_optic_sheath_diameter_measurement/assets/106801897/149cfd7c-10e6-4ce7-8b9c-e7a029d12e34)


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
performance of the models

