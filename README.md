# ADS Project Report Material

This repository contains supporting material for our project report.

## Repository Layout

```
├── README.md
├── replication
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   └── README.md
└── training
    ├── README.md
    ├── input
    │   ├── annotations
    │   │   ├── instances_train2014.json
    │   │   └── instances_val2014.json
    │   ├── coco_train2014
    │   │   ├── 1000.jpeg
    │   │   ├── 1001.jpeg
    ......
    │   └── coco_val2014
    │       ├── 1000.jpeg
    │       ├── 1001.jpeg
    ......
    ├── labelme2coco.py
    ├── output
    │   └── images
    │       ├── 1000.jpeg.pdf
    │       ├── 1001.jpeg.pdf
    ......
    └── requirements.txt
```

- `replication` folder contains resources about replicating the original paper.
- `training` folder contains resources about training model on our new data.