# 讓 .onnx 變成騰訊的形狀
## 修改 yolov8 官方檔案，因為有些函數 ncnn 還不支持
* ultralytics/nn/modules/block.py
![](block.png)

* ultralytics/nn/modules/head.py
![](head.png)

## .pt -> .onnx
![](export指令.png)