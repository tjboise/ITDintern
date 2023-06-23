
## Week1 Jun. 20 ~ Jun. 25

### 🌲Environment set up
- [x] GPU driver installment
- [ ] Install Cuda: It is a necessary for the pytorch to use the GPU in laptop which would make training faster -->need permission from ITD
- [x] Install Pytorch
- [x] Install some image related packages

### 🌳download all images
- [x] write a [python script](https://github.com/tjboise/ITDintern/blob/main/dataset%20construct.ipynb) based on David's code to download [pictures](https://511.idaho.gov/#:MyRoutes).


## 🌴A small demo for using YOLOV5 in car targeting
- Construct a dataset and annotate
- [x] Upload images (150 in total) to [app.cvat.ai](https://app.cvat.ai) which is an online image annotation website.
- [x] Annotate the images

<div align="left">
<img width="600" alt="image" src="https://github.com/tjboise/ITDintern/assets/95270677/5fe75c1a-4e86-4cb6-a6f0-af194b2e83d8">
</div>
      
- YOLOV5 training + testing
- [ ] Revise the YOLOV5 code according to our dataset and run the train.py
- [ ] A code to count the car numbers based on the results from YOLOV5
