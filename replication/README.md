## Replication of the original work

We ran mask r-cnn pre-trained model on validation images from COCO dataset.

### Command

This following command runs inference using a pre-trained model and on the images placed in coco_2014_minival directory. It runs on single GPU.

```
python tools/test_net.py \
    --cfg configs/12_2017_baselines/e2e_mask_rcnn_R-101-FPN_2x.yaml \
    TEST.WEIGHTS https://dl.fbaipublicfiles.com/detectron/35861858/12_2017_baselines/e2e_mask_rcnn_R-101-FPN_2x.yaml.02_32_51.SgT4y1cO/output/train/coco_2014_train:coco_2014_valminusminival/generalized_rcnn/model_final.pkl \
    NUM_GPUS 1
```

