cd ../data 
mkdir Flowers
cd Flowers


#https://www.robots.ox.ac.uk/~vgg/data/flowers/102/
wget https://www.robots.ox.ac.uk/~vgg/data/flowers/102/imagelabels.mat
wget https://www.robots.ox.ac.uk/~vgg/data/flowers/102/setid.mat
wget https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz

tar -xvf 102flowers.tgz

cd ..
mkdir iNaturalist
cd iNaturalist


#https://github.com/visipedia/inat_comp/tree/master/2017
wget https://ml-inat-competition-datasets.s3.amazonaws.com/2017/train_val_images.tar.gz

tar -xf train_val_images.tar.gz