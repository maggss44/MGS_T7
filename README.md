docker exec -it serene_hugle bash 
cd work/demo/09
mkdir data
mkdir data/raw
mkdir data/ini

docker cp ~/Downloads/yelp_dataset.tar serene_hugle:/home/jovyan/work/demo/09  

docker cp serene_hugle:/home/jovyan/work/demo/09/T7.ipynb ./