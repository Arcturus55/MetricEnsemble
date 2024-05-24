## AI+ Project

### Dataset

I used a dataset, which consists of the 2m temperature data of the whole year of 2022. There are 5 metircs in total and they are listed below. The ground truth is selected as era5.

origin  | metirc name
:--:    | :--:
cwao    | eccc
ecmf    | ecmwf
rjtd    | jma
egrr    | ukmo
kwbc    | necp

### Train the model
To train the model, simply run these commands in your terminal:
```
python3 train.py --model MODEL_NAME --data_path PATH_TO_DATASET > log.txt &
```