## Construction of the new data

### Dependencies

Install python dependencies using:

```
pip install -r requirements.txt
```

### Usage

Once the annotation on all the images is completed, we can convert labelme generated json to trainval.json

```
python labelme2coco.py images
```

This will generate a trainval.json. This is the COCO dataset annotation JSON file.