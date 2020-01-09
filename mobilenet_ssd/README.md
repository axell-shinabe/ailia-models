# Mobilenet_SSD

### input

![input_iamge](couple.jpg)

Shape(1, 3, 300, 300) Range:[0, 1]

### output

![output_image](annotated.png)


### usage

``` bash
python3 mobilenet_ssd.py mb1-ssd
```
or
```bash
python3 mobilenet_ssd.py mb2-ssd-lite
```
you can change input image path and save image path in `mobilenet_ssd.py`


### Reference

[pytorch-ssd](https://github.com/qfgaohao/pytorch-ssd)


### Framework
PyTorch 1.0 / 0.4


### Model Format
ONNX opset = 10