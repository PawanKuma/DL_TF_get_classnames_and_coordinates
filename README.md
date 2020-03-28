# DL_TF_get_classnames_and_coordinates
This is a complete inference generating code, where in you can specify a model, label file and threshold to get the detected class and bounding box cordinates.

#step_1:
Download visulasiation_util.py and replace the visualistaion_util file from tensorflw-model-research-object_detection-utils path with the downloaded one

#step_2: rerun 

$python setup.py build

$python setup.py install

#step_3: 

Load get_inference file as module

write code to pass image/frames through get_inference.get_roi_label function which returns roi and class_labels
