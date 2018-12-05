# Dataset_for_CV
training dataset preparation



### scalabel
**problem in uploading the data**
spin up another server to host the images and point the urls to there.  

in the folder with my images:  
python -m http.server 8001 . 

and then in my image_list.yml . 
- {url: http://localhost:8001/image.jpg} . 
