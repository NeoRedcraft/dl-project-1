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
- [Mendeley Data - Md Aiyub Ali: ](https://data.mendeley.com/datasets/yj35kjgrv3/1)
- [Kaggle - rohit_rawat25: ](https://www.kaggle.com/datasets/rohitrawat25/combined-fundus-images/data)
- [Kaggle - Kris Dcosta & bhavisha chafekar: ](https://www.kaggle.com/datasets/saketlad/armd-combined-dataset-fundus-and-oct/data)
- [Kaggle - iam_achal: ](https://www.kaggle.com/datasets/iamachal/fundus-image-dataset)
## 📄 File Description:
project-root/
│
├── src/                     # Main source code
│   ├── components/          # Reusable components or modules
│   ├── utils/               # Helper/utility functions
│   └── main.py              # Entry point script
│
├── data/                    # Dataset, raw files, assets
│   ├── raw/                 # Unprocessed data
│   └── processed/           # Cleaned/structured data
│
├── models/                  # Trained ML/DL models
│   └── best_model.pt
│
├── notebooks/               # Jupyter notebooks for experiments
│   └── analysis.ipynb
│
├── results/                 # Output logs, graphs, images
│   ├── charts/              # Plots/visualizations
│   └── metrics/             # Performance scores
│
├── scripts/                 # Bash or helper scripts
│   └── deploy.sh
│
├── tests/                   # Unit tests
│   └── test_utils.py
│
├── requirements.txt         # Dependencies list
├── README.md                # Documentation overview
├── .gitignore               # Ignored files list
└── LICENSE                  # License info
