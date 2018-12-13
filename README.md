# TensorFlow and Flask

crunched a few things together, maybe next build is an upload to recognition.

[Upload with flask](https://medium.com/@sightengine_/image-upload-and-moderation-with-python-and-flask-e7585f43828a)

you will need to pip install:
- flask

only went through the first bit ^  not built out yet
but you can run with:

```
export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```

[Object Detection](https://towardsdatascience.com/object-detection-with-10-lines-of-code-d6cb4d86f606)

you will need to pip install:

- tensorflow
- numpy
- scipy
- opencv-python
- pillow
- matplotlib
- h5py
- keras
- [imageai](https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.2/imageai-2.0.2-py3-none-any.whl)

images have been gitignored, download an image with traffic and move it to root call it `image.jpg`

try out `python3 FirstDetection.py`