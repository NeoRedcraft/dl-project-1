# Contributors:
* Felipe M. Panugan III - NeoRedcraft
* Liandro E. Refulle - liandrorefulle
* Prince Jeffery Villamil - princeVillamil
* Nicko Gabriel Baldo - NickoGabrielB
# Classifying and Segmenting Multiple Ocular Diseases Using Deep Learning Based on Retinal Imaging
This study presents a deep learning–based framework for the classification and segmentation of multiple ocular diseases using retinal images. 
The system employs the YOLOv12 segmentation architecture, trained on the RetinaVision dataset composed of curated fundus images annotated for cataract, 
age-related macular degeneration (AMD), and pathologic myopia. The dataset was divided into an 80-10-10 split for training, validation, and testing, respectively. 
After 606 epochs, the model achieved a mean Average Precision (mAP@0.5) of 0.93 and mAP@0.5:0.95 of 0.767, demonstrating both excellent localization accuracy and strong generalization across ocular disease classes. 
These results highlight YOLOv12’s capacity for simultaneous detection and segmentation, indicating its potential for real-time ophthalmic screening applications.
## 📊 Dataset:
- [Mendeley Data - Md Aiyub Ali: Fundus Image Dataset for Age-Related Macular Degeneration Disease Detection](https://data.mendeley.com/datasets/yj35kjgrv3/1)
- [Kaggle - rohit_rawat25: Multi Eye Disease Fundus Image Dataset (Combined)](https://www.kaggle.com/datasets/rohitrawat25/combined-fundus-images/data)
- [Kaggle - Kris Dcosta & bhavisha chafekar: ARMD Combined Dataset (Fundus and OCT)](https://www.kaggle.com/datasets/saketlad/armd-combined-dataset-fundus-and-oct/data)
- [Kaggle - iam_achal: Fundus Image Dataset](https://www.kaggle.com/datasets/iamachal/fundus-image-dataset)
## 📄 File Description:
<pre>
AI2-Project-AM2-HealthPath Discovery/
├── Evidence of model testing.pdf - Visual proof of the model testing, containing screenshots from the notebook, and the website  
├── IEEE Paper Final.pdf - The research paper written after conducting the study, the format is based on the IEEE conference paper template 
├── Latest_Final.ipynb - The methodology how the study is done. Google Colab Pro was used to train, validate, and test the model
├── runs/ - Generated during model training (containing model weights, logs, and results)
├── Test.v2i.yolov12/ - Dataset already spilt, pre-processed, and augmented by Roboflow
└── Web Deployment Code/ - For the Streamlit website deployment of the model
</pre>
