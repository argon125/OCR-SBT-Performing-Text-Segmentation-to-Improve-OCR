## Performing Text Segmentation to Improve OCR on Multi Scene Text

#### Official Repository of the Best Paper award-winning paper at the 5th International Conference on Artificial Intelligence and Speech Technology (AIST-2023)

Optical Character Recognition (OCR) is a revolutionary technique that aids machines in retrieving textual content from images to perform further analysis. However, OCR has its limitations, especially when dealing with degraded or low-quality images, which can impact the overall reliability of the text recognition process. Thus, the system’s accuracy is contingent upon the quality of the input (digital or handwritten documents). Efforts to modify the text detection and text recognition modules in existing OCRs fail to work in complex dynamic environments due to the complexity of the background information of the input data. Thus, a new first-of-its-kind annotated dataset called OCR-SBT for digital text segmentation is proposed in this work, along with a novel preprocessing pipeline using deep learning that performs text retrieval from images having varying and complex backgrounds using binary semantic segmentation. With quantitative metrics such as the DICE coefficient as high as 99.56%, the qualitative performance improvement of OCR has also been validated on real-world test samples containing varying contextual information to validate the model’s efficacy. Ablation experiments are also performed to determine the importance of super-resolution of input images using Stable Diffusion and ESRGAN. This work will help the research community to improve OCR for several real-world applications by alleviating the problems related to background contextual information obfuscating the text recognition module. 

![image](https://github.com/argon125/OCR_SBT-Performing-Text-Segmentation-to-Improve-OCR/assets/64146402/48d8737d-daaf-45bc-b936-ee63a51208e4)
Sample images and binary segmentation masks of the dataset introduced.

![image](https://github.com/argon125/OCR_SBT-Performing-Text-Segmentation-to-Improve-OCR/assets/64146402/92767323-5ae5-4d8d-b8ca-7c4edd1974a6)
Proposed approach to perform text segmentation and OCR.

![image](https://github.com/argon125/OCR_SBT-Performing-Text-Segmentation-to-Improve-OCR/assets/64146402/7b86b313-359a-4885-95a7-0e950b628097)
Predictions obtained by the UNet3+ architecture on super-resolution input text image

Link to Parer: https://link.springer.com/chapter/10.1007/978-3-031-75164-6_5
Link to the Dataset: https://drive.google.com/drive/folders/1aOPVgGTuuCZFeWKTROLwXjovRfi254S5?usp=sharing

Model weights can be made available on request: (mail to: arrun.sivasubramanian@gmail.com)

(Input images for training images are select images taken from the SyntheTiger repository. The masks were generated using colour k-means clustering)

### Authors: Arrun Sivasubramanian(1), Sheel Shah Rikesh(1), Akash Narayanaswamy(1,2), Rindhya C(1,2), Barathi Ganesh HB(1)

### Affiliation:

#### (1) Resilience Business Grids LLP, Coimbatore, India.
#### (2) Department of CSE, Sri Ramakrishna Engineering College, Coimbatore, India.
