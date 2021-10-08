# Social-Distancing-and-face-mask-detection
## Weights and dataset can be downloaded from the link below
[Weights & Dataset](https://drive.google.com/drive/folders/1X1gumNJy80tydmZuigJwtzia60Rv9CU7?usp=sharing)
</br>
</br>
## Weights folder location
Put weights inside folder yolo-coco/yolov3.weights

## Training
For training run the below command:
```
train_mask_detector.py -d "<dataset-folder-location>" -p "Output Data/plot.png" -m "models/<generate-model-filename>"
```
## Prediction
run the below command:
```
python main.py
```
