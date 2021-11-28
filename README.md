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

### Data

- concatenate [train_data_1.txt](https://github.com/IgorSondors/arcface-pytorch/blob/master/data/train_data_1.txt) and [train_data_2.txt](https://github.com/IgorSondors/arcface-pytorch/blob/master/data/train_data_2.txt) as one file train_data.txt and save that inside /data
