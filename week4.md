

#### Data clearning: 
Remove pictures without any cars. It is a very important step before we annotate the images. 
- If there are too many pictures without car, it will cause a waste in labor as we have to look through so many pictures without car. 
- Also, it is meaningless to the model. only the images with car can improve the model performance.

- [x] All the images on July 4th: 13386

-> after removing some broken file and pictures with no car, an amount of 4930 is left.

-> upload it to the app.cvat.ai




#### Annotation

![image](https://github.com/tjboise/ITDintern/assets/95270677/dc0ee6c7-3d46-412a-9675-8207cdd2f2bf)

Four classes: 
1. Motorcycles
2. Cars & light goods (cars, van)
3. other vehicles (truck)
4. Others (can't see the car but lights, especially for the night condition)
