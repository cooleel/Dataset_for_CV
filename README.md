# Dataset_for_CV

### Literature
#### Chest X-ray Disease Diagnosis 
[CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031)  
[SDFN: Segmentation-based Deep Fusion Network for Thoracic Disease Classification in Chest X-ray Images](https://arxiv.org/abs/1810.12959)






### Dataset
#### X-ray
- NIH Chest X-ray Dataset
- CheXpert Dataset
- JSRT Dataset




### training dataset preparation



### scalabel
**problem in uploading the data**   
spin up another server to host the images and point the urls to there.  

in the folder with my images:  
python -m http.server 8001 . 

and then in my image_list.yml . 
- {url: http://localhost:8001/image.jpg} . 
