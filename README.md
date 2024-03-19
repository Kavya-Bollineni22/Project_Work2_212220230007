## Tumor Spread Estimation in lungs using Medical Image Segmentation based on Deep Neural Networks

Tumor spread estimation in lungs employs Deep Neural Networks (DNNs) like U-Net on datasets such as Medical Segmentation Decathlon. It involves preprocessing medical images, training DNNs to map lung images to tumor segmentations, and deploying them for accurate tumor delineation. This method aids in assessing tumor size, shape, and spread, facilitating treatment planning and disease monitoring. It represents a promising approach in oncology, offering precise and efficient insights into lung cancer diagnosis and management.
## About
Tumor spread estimation in the lungs using medical image segmentation based on Deep Neural Networks (DNNs) is a cutting-edge approach in the field of medical imaging and oncology. This technique utilizes advanced computational methods to accurately identify and delineate tumor regions within lung images obtained from medical scans such as CT or MRI.
The process typically involves the use of a specific dataset tailored for medical image segmentation tasks, such as the Medical Segmentation Decathlon dataset, which provides annotated medical images for various organs and pathologies, including lung tumors. One commonly employed architecture for such tasks is the U-Net architecture, which has demonstrated remarkable performance in medical image segmentation tasks due to its ability to capture both local and global features effectively.
The workflow begins with preprocessing the medical images to enhance their quality and prepare them for segmentation. Subsequently, the U-Net architecture is trained on the annotated dataset, where it learns to map input lung images to corresponding tumor segmentation masks. During training, the network adjusts its parameters to minimize the discrepancy between predicted and ground-truth segmentations, optimizing its performance.
Once trained, the DNN model can be deployed to segment tumors in unseen lung images accurately. This segmentation facilitates tumor spread estimation by providing precise delineation of tumor boundaries, allowing clinicians to assess tumor size, shape, and spatial distribution. Furthermore, such automated segmentation aids in treatment planning, monitoring disease progression, and evaluating treatment efficacy.
## Features
1. Medical Image Segmentation: Utilizes cutting-edge techniques to segment lung images and accurately identify tumor regions.
2. Deep Neural Networks (DNNs): Leverages advanced DNN architectures like U-Net for robust and precise tumor segmentation.
3. Medical Segmentation Decathlon Dataset: Utilizes a curated dataset tailored for medical image segmentation tasks, providing annotated lung images for training and evaluation.
4. Tumor Spread Estimation: Enables clinicians to estimate tumor spread by precisely delineating tumor boundaries, aiding in treatment planning and disease monitoring.
5. Enhanced Precision: Offers high accuracy in tumor segmentation, providing detailed insights into tumor size, shape, and spatial distribution.

## Requirements
* Web Browser: Google Chrome, Mozilla Firefox, or Microsoft Edge for accessing Google Colab's online platform.
* Python: Ensure Python is installed on your HP laptop. You can download and install it from the official website.
* Stable Internet Connection: Reliable internet access is necessary to use Google Colab effectively.
* Google Account: Sign in with your Google account to access Google Colab and save your work on Google Drive.
* Medical Imaging: UNET architecture for the tumor segmentation in CT images of lungs.
## System Architecture
![Lung Tumor Segmentation](https://github.com/Kavya-Bollineni22/Project_Work2_212220230007/assets/75235813/f835d313-0bbf-437b-bb73-cae3c13d3716)

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

#### Output1 - Ground Truth Tumor Segmentation
![image](https://github.com/Kavya-Bollineni22/Project_Work2_212220230007/assets/75235813/db1d671f-f90e-46f6-a781-9cfc7e198291)

#### Output2 - Validation Mask Segmentation
![image](https://github.com/Kavya-Bollineni22/Project_Work2_212220230007/assets/75235813/bb5f87ec-4e7b-4dc6-a34d-4e013da9d64a)

#### Output3 - Test Mask Segmentation
![image](https://github.com/Kavya-Bollineni22/Project_Work2_212220230007/assets/75235813/3b08fa03-b51d-4a59-a40b-0b74d0fb9fc1)

#### Output4 - Predicted Segmentation image
![image](https://github.com/Kavya-Bollineni22/Project_Work2_212220230007/assets/75235813/e951a25a-21d9-40ce-bc6b-317dfb61cf8f)

## Results and Impact
1. Accurate Tumor Segmentation: The system can accurately segment lung tumor regions within medical images, providing precise delineation of tumor boundaries, leading to improved diagnostic accuracy.
2. Enhanced Treatment Planning: Clinicians can leverage the system's output for better treatment planning by assessing tumor size, shape, and spatial distribution, thus optimizing treatment strategies tailored to individual patients.
3. Streamlined Disease Monitoring: Automated tumor segmentation facilitates efficient disease monitoring, enabling clinicians to track tumor progression or regression over time more effectively, leading to timely interventions and improved patient outcomes.
4. Time and Cost Savings: By automating the segmentation process, the system reduces the manual effort required for tumor delineation, saving time for medical professionals and potentially reducing healthcare costs.

## Articles published / References
[1] Sarah E. Gerard, Jacode Hermann, Yi Xin, Kevin T. Martin, Davide Ippolito, Giacamo Bellani, Maurizio Cereda, "CT image segmentation for inflamed and fibrotic lungs using a multi-resolution convolutional neural network." (2021)
<br/>
<br/>
[2] Jiantao Pu, Bin Zheng, Joseph Ken Leader, Carl Fuhrman, Friedrich Knollmann, Amy Klym, David Gur, "Pulmonary Lobe Segmentation in CT Examinations using Implicit Surface Fitting." (2021)
<br/>
<br/>
[3] Zewei Zhang, Jialiang Ren, Xiuli Tao, Wei Tang, Shijun Zhao, Lina Zhou, Yao Huang, Jianwei Wang, Ning Wu, "Automatic Segmentation of pulmonary lobes on low-dose computed tomography using deep learning." (2021)
<br/>
<br/>
[4]	Ardila D, Kiraly AP, Bharadwaj S, et al. "End-to-end lung cancer screening with three-dimensional deep learning on low-dose chest computed tomography. Nature Medicine." (2019)
<br/>
<br/>
[5]	Setio AAA, Traverso A, de Bel T, et al., "Validation, comparison, and combination of algorithms for automatic detection of pulmonary nodules in computed tomography images: The LUNA16 challenge." Medical Image Analysis. (2017)
<br/>
<br/>
[6]	Zhang X, Xie Y, Xing F, et al. "Deep convolutional neural network for segmentation of thoracic organs-at-risk using cropped 3D images." Medical Physics. (2017)
<br/>
<br/>
[7]	Yan K, Wang X, Lu L, et al., "DeepLesion: Automated mining of large-scale lesion annotations and universal lesion detection with deep learning. Journal of Medical Imaging." (2018)
<br/>
<br/>
[8] Liang M, Tang W, Xu D, et al., "An automatic detection system of lung nodule based on multigroup patch-based deep learning network." Journal of Healthcare Engineering. (2017)
<br/>
<br/>
[9] Shen W, Zhou M, Yang F, et al., "Multi-scale convolutional neural networks for lung  nodule classification." In: IEEE International Symposium on Biomedical Imaging. (2015)
<br/>
<br/>
[10] Setio AAA, Ciompi F, Litjens G, et al., "Pulmonary nodule detection in CT images: False positive reduction using multi-view convolutional networks." IEEE Transactions on Medical Imaging. (2016)



