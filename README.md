# P2-ML-GCN and RP2-ML-GCN.pytorch

### Requirements
Please, install the following packages
- numpy
- torch-0.3.1
- torchnet
- torchvision-0.2.0
- tqdm

### Download pretrain models
checkpoint/coco ([GoogleDrive](https://drive.google.com/open?id=1ivLi1Rc-dCUmN1ProcMk76zxF1DSvlIk))

checkpoint/voc ([GoogleDrive](https://drive.google.com/open?id=1lhbmW5g-Mo9KgI07nmc1kwSbEnb6t-YA))

### Train Voc2007

### Train MS-COCO

### Test Voc2007
```sh
python3 demo_voc2007_gcn.py data/voc --image-size 448 --batch-size 16 -e --resume checkpoint/voc/voc_checkpoint.pth.tar
```

### Test MS-COCO
```sh
python3 demo_coco_gcn.py data/coco --image-size 448 --batch-size 8 -e --resume checkpoint/coco/coco_checkpoint.pth.tar
```

## Reference
This project is based on https://github.com/Megvii-Nanjing/ML-GCN

## Tips
If you have any questions about our work, please do not hesitate to contact us.

