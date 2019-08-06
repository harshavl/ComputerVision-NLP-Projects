
# Object Detector using HOG filter

1. install dlib library
2. Use CALTECH-101 images and annotations dataset.
3. Train the object detector using SVM ML algorithm and visualize the HOD filter.
4. Testing Object Detector.

## Usage
```
python train_detector.py --class sunflower_images/ --annotations sunflower_annotations --output output/sun_flower_detector.svm

python test_detector.py --detector output/sun_flower_detector.svm --testing sun_flower_testing/

```
