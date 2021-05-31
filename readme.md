# Auto-annotate
### Welcome to the auto-annotate images for TensorFlow object detection!

You are tired to label your images by hand to work with object detection? So, this project will make your life easier, just annotate some images and let the machine do the rest for you!

## Requirements
- You will need to [clone the TensorFlow repository](https://github.com/tensorflow/models)
- Install the [dependencies](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/tensorflow-1.14/install.html) for object detection

**note:** This project is compatible with 2.0>TF>=1.4
## How to run
- Copy and paste the file generate_xml.py and visualization_utils.py into the **research/object_detection/utils** in the tensorflow repo.
- Add your pre-treined model and label map into the 'graphs' folder.
- Add the images you want to label into the images folder
- Change the xml path in generate_xml.py to put your own local path.
- Inside the auto_annotate folder run: **python3 scripts/detection_images.py**

