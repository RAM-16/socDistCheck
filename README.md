# socDistCheck--YOLOv5

### Categorizing individuals as high or low risk based on their proximity to others.

## Requirements


Python 3.7 or later with all `requirements.txt` dependencies installed, including `torch >= 1.5`. To install run:
```bash
$ pip install -U -r requirements.txt
```


---



## Usage


Run on a single video file


```bash
$ python detect.py --source ./inference/videos/videofile.mp4
```


Run on all video files inside a folder


```bash
$ python detect.py --source ./inference/videos/
```


**Options**

*Add using '--'*


```
agnostic_nms=False, augment=False, classes=None, conf_thres=0.4, device='', fourcc='mp4v', half=False, img_size=640, iou_thres=0.5, output='inference/output', save_txt=False, source='./inference/images/', view_img=False, weights='yolov5s.pt'
```


---


## Output

![](output.gif)


---


### TODO

- [x] Remove a bug which classifies people as low risk instead of high.
- [x] Add live video support
- [x] Add image support
