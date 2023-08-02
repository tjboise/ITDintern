## July 31 - Aug 4

Results comparison:

|No.| Dataset  | train:val | Model | Epochs| Batch Size|weight|Hyper parameters| mAP@0.5|Training Time(hours)|Details|
|:---:| :-----:  | :-------: |:-----:|:-----:|:---------:|:------:|:-----------:|:----:|:---:|:----:|
|1| 1979 (David + TJ)  | 8:2| YOLOV5 |300|8|yolov5s.pt|[hyp](../results/exp16/hyp.yaml)|0.727|4.5|[exp16](../results/exp16)|
|2| 2867 (David + TJ +Taylor)  |  8:2| YOLOV5|300|8|yolov5s.pt|[hyp](../results/exp17/hyp.yaml)|0.623 |early stops(no improvement observed in last 100 epochs)| [exp17](../results/exp17) |

There are some improvements from 1 to 2 like: 

<div align="center">
1: <img src="https://github.com/tjboise/ITDintern/assets/95270677/bd6f2bcc-0be1-4466-bfaf-ae617e8c8feb" width=40%/> 
2: <img src="https://github.com/tjboise/ITDintern/assets/95270677/888c178f-a06b-4012-a36b-4bab81f3c2e0" width=40%/>
</div>
but also: 
<div align="center">
1: <img src="https://github.com/tjboise/ITDintern/assets/95270677/c7b13e6c-48cb-40d7-8b67-60f80d7a3ae8" width=40%/> 
2: <img src="https://github.com/tjboise/ITDintern/assets/95270677/42849452-2e02-4ab9-a549-2ad27d4ffdaf" width=40%/>
</div>

