# Dataset_for_CV

### Literature
#### Chest X-ray Disease Diagnosis 
[CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031)  
[SDFN: Segmentation-based Deep Fusion Network for Thoracic Disease Classification in Chest X-ray Images](https://arxiv.org/abs/1810.12959)

#### Table detection and table structure recognition
[TableBank: Table Benchmark for Image-based Table Detection and Recognition](https://arxiv.org/abs/1903.01949)
[Rethinking Table Recognition using Graph Neural Networks](https://arxiv.org/pdf/1905.13391v2.pdf)






### Dataset
#### X-ray
- [NIH Chest X-ray Dataset](https://www.kaggle.com/nih-chest-xrays/data)
- [CheXpert Dataset](https://stanfordmlgroup.github.io/competitions/chexpert/)
- [JSRT Dataset](http://db.jsrt.or.jp/eng.php)

#### Table
- [TableBank](https://doc-analysis.github.io/)
- [2013ICDAR table competition dataset](https://roundtrippdf.com/en/downloads/)


### training dataset preparation

### scalabel
**problem in uploading the data**   
spin up another server to host the images and point the urls to there.  

in the folder with my images:  
python -m http.server 8001 . 

and then in my image_list.yml . 
- {url: http://localhost:8001/image.jpg} . 
