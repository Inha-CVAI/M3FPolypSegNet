# M3FPolypSegNet: Multi-Frequency Feature Fusion Segmentation Network for Polyp Localization in Colonoscopy Images
Available code for ICIP2023
![M3FPolypSegNet](https://user-images.githubusercontent.com/77310264/223346757-0774fd2f-4dff-4753-a66c-1baa40ab32f2.png)

## Abstract
Polyp segmentation is crucial for preventing colorectal cancer a common type of cancer. Deep learning has been used to segment polyps automatically, which reduces the risk of misdiagnosis. Localizing small polyps in colonoscopy images is challenging because of its complex characteristics, such as color, occlusion, and various shapes of polyps. To address this challenge, a novel frequency-based fully convolutional neural network, \textit{Multi-Frequency Feature Fusion Polyp Segmentation Network (M3FPolypSegNet)} was proposed to decompose the input image into low/high/full-frequency components to use the characteristics of each component. We used three independent multi-frequency encoders to map multiple input images into a high-dimensional feature space. In the \textit{Frequency-ASPP Scalable Attention Module (F-ASPP SAM)}, ASPP was applied between each frequency component to preserve scale information. Subsequently, scalable attention was applied to emphasize polyp regions in a high-dimensional feature space. Finally, we designed three multi-task learning (i.e., region, edge, and distance) in four decoder blocks to learn structural characteristics of the region. An average IoU improvement of 1.63% was achieved compared with the existing state-of-the-art model PraNet on two polyp segmentation benchmark datasets (CVC-ClinicDB and BKAI-IGH-NeoPolyp).
