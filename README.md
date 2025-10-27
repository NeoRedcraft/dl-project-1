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
-  [Mendeley Data - Md Aiyub Ali: Fundus Image Dataset for Age-Related Macular Degeneration Disease Detection](https://data.mendeley.com/datasets/yj35kjgrv3/1)
-  [Kaggle - rohit_rawat25: Multi Eye Disease Fundus Image Dataset (Combined)](https://www.kaggle.com/datasets/rohitrawat25/combined-fundus-images/data)
-  [Kaggle - Kris Dcosta & bhavisha chafekar: ARMD Combined Dataset (Fundus and OCT)](https://www.kaggle.com/datasets/saketlad/armd-combined-dataset-fundus-and-oct/data)
-  [Kaggle - iam_achal: Fundus Image Dataset](https://www.kaggle.com/datasets/iamachal/fundus-image-dataset)
-  [Roboflow - (Our Group's Combined Dataset)](https://universe.roboflow.com/felipe-m-panugan-iii/fundus-detection-lwc5t/dataset/2)
## 📄 File Description:
<pre>
📂 AI2-Project-AM2-HealthPath Discovery/
├── 📄 Evidence of model testing.pdf
│     ↳ Visual proof of model testing using screenshots from the notebook and website  
├── 📄 IEEE Paper Final.pdf
│     ↳ Research paper following the IEEE conference format
├── 📓 Latest_Final.ipynb
│     ↳ Implementation on notebook showing dataset, training, validation, and testing (Google Colab Pro)
├── 📁 runs/
│     ↳ Contains auto-generated training outputs (weights, logs, metrics, results)
├── 📁 Test.v2i.yolov12/
│     ↳ Pre-processed, split, and augmented dataset (via Roboflow)
└── 💻 Web Deployment Code/
      ↳ Streamlit files used for deployment of the trained model
</pre>
## 🌐 Web Deployment

Upload a retinal fundus image for automated detection of **Cataract**, **Age-related Macular Degeneration (AMD)**, or **Pathological Myopia**.  
If no abnormalities are detected, the image is most likely **healthy**.

🔗 **Live Demo:**  
https://retinavision.streamlit.app/#detection-info

