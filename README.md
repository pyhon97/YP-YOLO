# YP-YOLO ：A data set for target detection of young peach fruits
 [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## Introduction
This repository is built for:

YP-YOLO dataset includes young peach fruits in different scenes.Here we have only presented some sample images from the dataset. If you need them, please contact us to obtain more. 
## How to use
To train a network on the YP-YOLO dataset make sure that you download the code first from [yolov11](https://github.com/ultralytics/ultralytics). And then clone this repository to yolov11 folder and  train a yolov11 network with the commands below.

```
# Clone yolov11 repo and install requirements.txt
git clone https://github.com/ultralytics/ultralytics  # clone
cd yolov11
pip install -r requirements.txt  # install
```

```
# Clone this repository to yolov11 folder
git clone https://github.com/python97/YP-YOLO.
```

```
# Train yolov11
yolo detect train model=yolov11s.yaml data=dataset.yaml  epochs=150 imgsz=640
```

## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
