# A yolo format face mask detection dataset

 [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

The dataset includes two kinds of data: wearing mask and not wearing mask. 

The yolo format includes two types of tags:"Mask" and "No Mask" 

The data set includes: railway station, airport, chemical laboratory, precision machinery manufacturing workshop, hospital and many other places where wearing mask needs to be standardized. 

This dataset contains more than 2,500 images.

<center class="half">
<img src=".\demo\origin.jpg" alt="origin" style="zoom:50%;" /><img src=".\demo\result.jpg" alt="result" style="zoom:50%;" />
</center>


## How to use 

To train a network on the face mask detection dataset make sure that you download the code first from [yolov5](https://github.com/ultralytics/yolov5). And then clone this repository to yolov5 folder and  train a yolov5 network with the commands below.

```
# Clone yolov5 repo and install requirements.txt in a Python>=3.7.0 environment, including PyTorch>=1.7.
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
```

```
# Clone this repository to yolov5 folder
git clone https://github.com/LforikC/face-mask-dataset
```

```
# Train yolov5
python train.py --data face-mask-dataset/dataset.yaml --epochs 300 --cfg yolov5s.yaml
```



## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

