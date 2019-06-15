# Converter (cfg-->h5)
Reads Darknet config and weights and creates Keras model with TF backend.
Inspired from : [YAD2K](https://github.com/allanzelener/YAD2K/blob/master/yad2k.py) and [Convert](https://github.com/qqwweee/keras-yolo3/blob/master/convert.py)

These converters aren't compatible with tensorflow 2.0 backend and they don't have the code to convert a avgpool layer.
So I have changed the code a bit so that the new converter is now compatible with Tensorflow 2.0 and can convert avgpool layer too.

## How to use

Open cmd and type:

```
python convert2.py darknet53.cfg darknet53.weights darknet53.h5
```
## Advantages
- Supports TF 2.0
- Supports YOLO_v3
