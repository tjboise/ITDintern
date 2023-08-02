## July 31 - Aug 4

Results comparison:

|No.| Dataset  | train:val | Model | Epochs| Batch Size|weight|Hyperparameters| mAP@0.5|Training Time(hours)|Details|
|:---:| :-----:  | :-------: |:-----:|:-----:|:---------:|:------:|:-----------:|:----:|:---:|:----:|
|1| 1979 (David + TJ)  | 8:2| YOLOV5 |300|8|yolov5s.pt|[hyp](../results/exp16/hyp.yaml)|0.727|4.5|[exp16](../results/exp16)|
|2| 2867 (David + TJ +Taylor)  |  8:2| YOLOV5|300|8|yolov5s.pt|0.01-0.0001|0.623 |early stops(no improvement observed in last 100 epochs)| [exp17]() |
