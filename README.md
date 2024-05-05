# VisDrone-yolov8
 Many yolov8 model  are trained on the VisDrone dataset.

## Train
You can train according to my parameter settings or download my model. All model parameters were trained on a single A40 GPU.

## Performance
| model | input size | other hyper-parameters | val mAP50 | val mAP50-95 | test mAP50 | test mAP50-95 | model & log |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |  :-: | 
| yolov8s | 640 | default | 0.404| 0.24| 0.32| 0.184| [Google](https://drive.google.com/drive/folders/1PV44NEOVTb_M_okL3Ehpl989hV29I-gg?usp=drive_link)|
| yolov8l | 640 | default | 0.453 | 0.278| 0.361 | 0.213 |  [Google](https://drive.google.com/drive/folders/1Ufe8tFD2gTSh5EaeMa2BkTC4ZSrvG20S?usp=drive_link) |
| yolov8s | 960 | default | 0.496 | 0.308 | 0.396 | 0.234 |  [Google](https://drive.google.com/drive/folders/1IRzPuld_P42tR3v8mtjDwJlDW-vDfk8P?usp=drive_link) |
| yolov8s | 960 & mutil-scale| default | 0.492 | 0.304 | 0.399 | 0.236 |  [Google](https://drive.google.com/drive/folders/1fMmcbmD7xuKQwYLTmVDoGLWzjuSspyj3?usp=drive_link) |
| yolov8s-p2 | 960 | default | 0.519 | 0.321 |  0.417 | 0.244 |  [Google](https://drive.google.com/drive/folders/1rNy1lIe2FLOQUzh8I8aTt9aG3gYQ1IJ1?usp=drive_link) |
| yolov8s-p2 | 960 | minxup=0.4 | 0.522 | 0.325 | 0.431| 0.255 |  [Google](https://drive.google.com/drive/folders/1fYgmNKjObD1GCigl68geznu6rKxr7X-k?usp=drive_link) |
| yolov8s-p2 | 960 | minxup=0.4, val iou=0.6| 0.531 | 0.327 | 0.437 |  0.256 |  [Google](https://drive.google.com/drive/folders/1fYgmNKjObD1GCigl68geznu6rKxr7X-k?usp=drive_link) |



## Other failed attempts
- copy_paste
- reduce image scale (+/- gain)
