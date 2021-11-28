# arcface-pytorch
pytorch implement of arcface 

### Env

- conda create -n arcface python=3.8 -y
- conda activate arcface
- conda install pytorch=1.9.1 torchvision torchaudio cudatoolkit=10.2 -c pytorch -y
- pip install opencv-python
- pip install visdom
- pip install matplotlib
- pip install scikit-learn
- pip install graphviz
- pip install jupyter

### Data and paths

- concatenate [train_data_1.txt](https://github.com/IgorSondors/arcface-pytorch/blob/master/data/train_data_1.txt) and [train_data_2.txt](https://github.com/IgorSondors/arcface-pytorch/blob/master/data/train_data_2.txt) as one file train_data.txt and save that inside /data
- download casia_faces and lwf [datasets](https://data.oz-services.ru/download/oz/test.tar.gz) (if the link is broke check [LFW](http://vis-www.cs.umass.edu/lfw/),[CASIA WebFace](https://arxiv.org/pdf/1411.7923.pdf))
- change paths [train_root](https://github.com/IgorSondors/arcface-pytorch/blob/58c0902338451daafca8f3ba91fdf51cd1a2b811/config/config.py#L14), [train_list](https://github.com/IgorSondors/arcface-pytorch/blob/58c0902338451daafca8f3ba91fdf51cd1a2b811/config/config.py#L15), [lfw_root](https://github.com/IgorSondors/arcface-pytorch/blob/58c0902338451daafca8f3ba91fdf51cd1a2b811/config/config.py#L21), [lfw_test_list](https://github.com/IgorSondors/arcface-pytorch/blob/58c0902338451daafca8f3ba91fdf51cd1a2b811/config/config.py#L22), [test_model_path](https://github.com/IgorSondors/arcface-pytorch/blob/9ea30c999c23a4d6d7b7af2c55975f9d74f5fad3/config/config.py#L26)

### Weights

- [10 epochs link](https://drive.google.com/file/d/1F_6vIFyrfy7s5tcarJBSDVdhAU6nFqP1/view?usp=sharing)

### Train from scratch

- cd arcface-pytorch
- python train.py

### Results

- far/frr plot and model evaluation [there](https://github.com/IgorSondors/arcface-pytorch/blob/master/plot_far_frr.ipynb)
