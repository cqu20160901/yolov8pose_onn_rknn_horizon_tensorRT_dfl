# yolov8pose_onn_rknn_horizon_tensorRT_dfl
yolov8pose 部署版本，将DFL放在后处理中，便于移植不同平台（onnx、tensorRT、rknn、Horizon），全网部署最简单、速度最快的部署方式。


导出 onnx 参考链接 [【yolov8-obb 旋转目标检测 瑞芯微RKNN芯片部署、地平线Horizon芯片部署、TensorRT部署】](https://blog.csdn.net/zhangqian_1/article/details/139437315)

**特别说明：本示例提供的代码只适用按照对应参考导出的onnx，其它方式导出onnx自行写后处理。**

# 文件夹结构说明

yolov8pose_onnx：onnx模型、测试图像、测试结果、测试demo脚本

yolov8pose_TensorRT：TensorRT版本模型、测试图像、测试结果、测试demo脚本、onnx模型、onnx2tensorRT脚本(tensorRT-7.2.3.4)

yolov8pose_rknn：rknn模型、测试（量化）图像、测试结果、onnx2rknn转换测试脚本

yolov8pose_horizon：地平线模型、测试（量化）图像、测试结果、转换测试脚本、测试量化后onnx模型脚本

# 测试结果

![image](https://github.com/cqu20160901/yolov8pose_onn_rknn_horizon_tensorRT_dfl/blob/main/yolov8pose_onnx/test_onnx_result.jpg)

