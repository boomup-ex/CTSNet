# CTSNet
Automated Segmentation and Morphological Measurement of Carpal Tunnel Tissues using Edge-Guided Dual-Stream Network

Accurate segmentation and quantification of carpal tunnel tissues, particularly the median nerve, are crucial for diagnosing and treating carpal tunnel syndrome (CTS). Despite the promising potential of magnetic resonance imaging (MRI) in revealing CTS characteristics, challenges such as heavy artefacts, small lesion features, and extensive image volumes have hindered its clinical utility. This study proposes an automated framework leveraging a dual-stream encoding model that integrates convolutional neural networks (CNNs) and self-attention mechanisms to effectively segment carpal tunnel tissues from MRI images. An edge-guidance module is introduced to enhance the model's performance, particularly in identifying delicate tissue edges, by utilizing edge information as explicit supervision. Furthermore, a medium-scale feature extraction module is designed to capture rich features across multiple scales. Experimental results on a dataset comprising 1,426 wrist MRI images demonstrate the proposed method's efficacy, achieving a Dice Similarity Coefficient (DSC) of approximately 0.92 and a mean Intersection over Union (mIoU) of 85.93%, outperforming state-of-the-art segmentation methods. Based on these precise segmentation results, seven morphological parameters are automatically measured, with an average correlation coefficient exceeding 0.92 compared to manual measurements. This study underscores the potential of automated MRI image segmentation and quantitative analysis in enhancing the efficiency of CTS diagnosis and treatment.

Meanwhile，we constructed a wrist MRI database to test the effectiveness of the proposed wrist canal tissue segmentation model, with data sourced from Shanxi Provincial People's Hospital.
For the purpose of protecting patient privacy, the data provider does not allow open source access to the dataset.

Our research has been summarized and submitted to The Visual Computer as an article titled:"Automated Segmentation and Morphological Measurement of Carpal Tunnel Tissues using Edge-Guided Dual-Stream Network"

The output results of the model are shown below：

![image](https://github.com/user-attachments/assets/0c385c5d-e565-4a92-8cd7-171d34d830a9)

Framework of the proposed model. 



![image](https://github.com/user-attachments/assets/e17cf851-ca2d-48fb-a25c-40a3fcfa9451)

Segmentation visualization results of the MRI carpal tunnel, The first column shows the original MRI, the second through fifth columns show the segmentation results of other state-of-the-art methods, the sixth shows the segmentation results of proposed method in this paper, the last column shows the manual segmentation by the clinician.




![image](https://github.com/user-attachments/assets/87ce8fd0-81ee-4df5-b662-a77ccfca0993)

Test results on the dataset used for evaluation. The proposed method continues to demonstrate robust segmentation outcomes for both modalities across additional datasets, substantiating its exceptional generalisation capabilities.
