# 昇腾 NPU 验证模型

飞桨框架在昇腾 NPU 上通过精度验证的模型情况如下：

* PaddleX 使用文档详见：[PaddleX 多硬件使用](https://github.com/PaddlePaddle/PaddleX/blob/release/3.0-beta1/docs/other_devices_support/multi_devices_use_guide.md)
* PaddleNLP 大语言模型多硬件使用文档详见：[PaddleNLP NPU 大语言模型使用文档](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/llm/npu)
* 如果您适配/验证过更多模型，欢迎按照此 [贡献教程](https://github.com/PaddlePaddle/PaddleX/blob/aba62bfb45f7873a5b1285c5423b20a40468a420/docs/tutorials/hardware_support/how_to_contribute.md) 向飞桨开源社区贡献适配结果，我们验证后会更新本模型验证列表

| 模型库 | 模型类型 | 模型名称 | 训练 | 推理 |
| - | - | - | - | - |
| PaddleX | 图像分类 | [ResNet18](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ResNet18.yaml) | √ | √ |
| PaddleX | 图像分类 | [ResNet34](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ResNet34.yaml) | √ | √ |
| PaddleX | 图像分类 | [ResNet50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ResNet50.yaml) | √ | √ |
| PaddleX | 图像分类 | [ResNet101](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ResNet101.yaml) | √ | √ |
| PaddleX | 图像分类 | [ResNet152](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ResNet152.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x0_25](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x0_25.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x0_35](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x0_35.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x0_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x0_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x0_75](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x0_75.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x1_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x1_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x1_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x1_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x2_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x2_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNet_x2_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNet_x2_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNetV2_base](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNetV2_base.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNetV2_small](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNetV2_small.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-LCNetV2_large](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-LCNetV2_large.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV1_x0_25](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV1_x0_25.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV1_x0_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV1_x0_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV1_x0_75](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV1_x0_75.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV1_x1_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV1_x1_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV2_x0_25](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV2_x0_25.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV2_x0_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV2_x0_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV2_x1_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV2_x1_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobilenetV2_x1_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV2_x1_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobilenetV2_x2_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV2_x2_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_small_x0_35](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_small_x0_35.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_small_x0_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_small_x0_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_small_x0_75](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_small_x0_75.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_small_x1_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_small_x1_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_small_x1_25](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_small_x1_25.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_large_x0_35](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_large_x0_35.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_large_x0_5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_large_x0_5.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_large_x0_75](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_large_x0_75.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_large_x1_0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_large_x1_0.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV3_large_x1_25](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV3_large_x1_25.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV4_conv_small](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV4_conv_small.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV4_conv_medium](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV4_conv_medium.yaml) | √ | √ |
| PaddleX | 图像分类 | [MobileNetV4_conv_large](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/MobileNetV4_conv_large.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNet_small](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNet_small.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNet_tiny](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNet_tiny.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B0](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B0.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B1](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B1.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B2](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B2.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B3](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B3.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B4](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B4.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B5](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B5.yaml) | √ | √ |
| PaddleX | 图像分类 | [PP-HGNetV2-B6](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/PP-HGNetV2-B6.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_base_patch4_window7_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_base_patch4_window7_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_small_patch4_window7_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_small_patch4_window7_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_tiny_patch4_window7_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_tiny_patch4_window7_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_base_patch4_window12_384](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_base_patch4_window12_384.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_large_patch4_window7_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_large_patch4_window7_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [SwinTransformer_large_patch4_window12_384](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/SwinTransformer_large_patch4_window12_384.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_tiny](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_tiny.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_Small](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_small.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_base_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_base_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_base_384](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_base_384.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_large_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_large_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [ConvNeXt_large_384](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/ConvNeXt_large_384.yaml) | √ | √ |
| PaddleX | 图像分类 | [CLIP_vit_base_patch16_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/CLIP_vit_base_patch16_224.yaml) | √ | √ |
| PaddleX | 图像分类 | [CLIP_vit_large_patch14_224](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/image_classification/CLIP_vit_large_patch14_224.yaml) | √ | √ |
| PaddleX | 图像多标签分类 | [PP-HGNetV2-B0_ML](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/multilabel_classification/PP-HGNetV2-B0_ML.yaml) | √ | √ |
| PaddleX | 图像多标签分类 | [PP-HGNetV2-B4_ML](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/multilabel_classification/PP-HGNetV2-B4_ML.yaml) | √ | √ |
| PaddleX | 图像多标签分类 | [PP-HGNetV2-B6_ML](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/multilabel_classification/PP-HGNetV2-B6_ML.yaml) | √ | √ |
| PaddleX | 图像多标签分类 | [CLIP_vit_base_patch16_448_ML](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/multilabel_classification/CLIP_vit_base_patch16_448_ML.yaml) | √ | √ |
| PaddleX | 目标检测 | [PP-YOLOE_plus-S](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PP-YOLOE_plus-S.yaml) | √ | √ |
| PaddleX | 目标检测 | [PP-YOLOE_plus-M](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PP-YOLOE_plus-M.yaml) | √ | √ |
| PaddleX | 目标检测 | [PP-YOLOE_plus-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PP-YOLOE_plus-L.yaml) | √ | √ |
| PaddleX | 目标检测 | [PP-YOLOE_plus-X](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PP-YOLOE_plus-X.yaml) | √ | √ |
| PaddleX | 目标检测 | [RT-DETR-R18](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/RT-DETR-R18.yaml) | √ | √ |
| PaddleX | 目标检测 | [RT-DETR-R50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/RT-DETR-R50.yaml) | √ | √ |
| PaddleX | 目标检测 | [RT-DETR-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/RT-DETR-L.yaml) | √ | √ |
| PaddleX | 目标检测 | [RT-DETR-H](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/RT-DETR-H.yaml) | √ | √ |
| PaddleX | 目标检测 | [RT-DETR-X](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/RT-DETR-X.yaml) | √ | √ |
| PaddleX | 目标检测 | [PicoDet-XS](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PicoDet-XS.yaml) | √ | √ |
| PaddleX | 目标检测 | [PicoDet-S](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PicoDet-S.yaml) | √ | √ |
| PaddleX | 目标检测 | [PicoDet-M](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PicoDet-M.yaml) | √ | √ |
| PaddleX | 目标检测 | [PicoDet-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/PicoDet-L.yaml) | √ | √ |
| PaddleX | 目标检测 | [CenterNet-DLA34](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/CenterNet-DLA-34.yaml) | √ | √ |
| PaddleX | 目标检测 | [CenterNet-ResNet50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/CenterNet-ResNet50.yaml) | √ | √ |
| PaddleX | 目标检测 | [FCOS-ResNet50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FCOS-ResNet50.yaml) | √ | √ |
| PaddleX | 目标检测 | [DETR-R50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/DETR-R50.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet34-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet34-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet50.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet50-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet50-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet50-vd-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet50-vd-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet50-vd-SSLDv2-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet50-vd-SSLDv2-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet101](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet101.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNet101-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNet101-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-ResNeXt101-vd-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-ResNeXt101-vd-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [FasterRCNN-Swin-Tiny-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/FasterRCNN-Swin-Tiny-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [YOLOv3-DarkNet53](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/YOLOv3-DarkNet53.yaml) | √ | √ |
| PaddleX | 目标检测 | [YOLOv3-ResNet50_vd-DCN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/YOLOv3-ResNet50_vd_DCN.yaml) | √ | √ |
| PaddleX | 目标检测 | [YOLOv3-MobileNet-V3](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/YOLOv3-MobileNetV3.yaml) | √ | √ |
| PaddleX | 目标检测 | [Cascade-FasterRCNN-ResNet50-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/Cascade-FasterRCNN-ResNet50-FPN.yaml) | √ | √ |
| PaddleX | 目标检测 | [Cascade-FasterRCNN-ResNet50-vd-SSLDv2-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/object_detection/Cascade-FasterRCNN-ResNet50-vd-SSLDv2-FPN.yaml) | √ | √ |
| PaddleX | 图像检索 | [PP-ShiTuV2_rec_CLIP_vit_base](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/general_recognition/PP-ShiTuV2_rec_CLIP_vit_base.yaml) | √ | √ |
| PaddleX | 图像检索 | [PP-ShiTuV2_rec_CLIP_vit_large](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/general_recognition/PP-ShiTuV2_rec_CLIP_vit_large.yaml) | √ | √ |
| PaddleX | 主体检测 | [PP-ShiTuV2_det](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/mainbody_detection/PP-ShiTuV2_det.yaml) | √ | √ |
| PaddleX | 行人检测 | [PP-YOLOE-S_human](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/human_detection/PP-YOLOE-S_human.yaml) | √ | √ |
| PaddleX | 行人检测 | [PP-YOLOE-L_human](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/human_detection/PP-YOLOE-L_human.yaml) | √ | √ |
| PaddleX | 车辆检测 | [PP-YOLOE-L_vehicle](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/vehicle_detection/PP-YOLOE-L_vehicle.yaml) | √ | √ |
| PaddleX | 图像异常检测 | [STFPM](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/anomaly_detection/STFPM.yaml) | √ | √ |
| PaddleX | 小目标检测 | [PP-YOLOE_plus_SOD-S](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/small_object_detection/PP-YOLOE_plus_SOD-S.yaml) | √ | √ |
| PaddleX | 小目标检测 | [PP-YOLOE_plus_SOD-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/small_object_detection/PP-YOLOE_plus_SOD-L.yaml) | √ | √ |
| PaddleX | 小目标检测 | [PP-YOLOE_plus_SOD-largesize-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/small_object_detection/PP-YOLOE_plus_SOD-largesize-L.yaml) | √ | √ |
| PaddleX | 语义分割 | [Deeplabv3-R50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/Deeplabv3-R50.yaml) | √ | √ |
| PaddleX | 语义分割 | [Deeplabv3-R101](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/Deeplabv3-R101.yaml) | √ | √ |
| PaddleX | 语义分割 | [Deeplabv3_Plus-R50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/Deeplabv3_Plus-R50.yaml) | √ | √ |
| PaddleX | 语义分割 | [Deeplabv3_Plus-R101](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/Deeplabv3_Plus-R101.yaml) | √ | √ |
| PaddleX | 语义分割 | [PP-LiteSeg-T](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/PP-LiteSeg-T.yaml) | √ | √ |
| PaddleX | 语义分割 | [OCRNet_HRNet-W48](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/semantic_segmentation/OCRNet_HRNet-W48.yaml) | √ | √ |
| PaddleX | 实例分割 | [PPYOLOE_Seg-S](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/PP-YOLOE_seg-S.yaml) | √ | √ |
| PaddleX | 实例分割 | [SOLOv2](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/SOLOv2.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-ResNet50](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNet50.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-ResNet50-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNet50-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-ResNet50-vd-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNet50-vd-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-ResNet101-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNet101-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-ResNet101-vd-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNet101-vd-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [MaskRCNN-MaskRCNN-ResNeXt101-vd-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/MaskRCNN-ResNeXt101-vd-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [Cascade-MaskRCNN-ResNet50-vd-SSLDv2-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Cascade-MaskRCNN-ResNet50-vd-SSLDv2-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [Cascade-MaskRCNN-ResNet50-FPN](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Cascade-MaskRCNN-ResNet50-FPN.yaml) | √ | √ |
| PaddleX | 实例分割 | [Mask-RT-DETR-H](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Mask-RT-DETR-H.yaml) | √ | √ |
| PaddleX | 实例分割 | [Mask-RT-DETR-L](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Mask-RT-DETR-L.yaml) | √ | √ |
| PaddleX | 实例分割 | [Mask-RT-DETR-M](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Mask-RT-DETR-M.yaml) | √ | √ |
| PaddleX | 实例分割 | [Mask-RT-DETR-X](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Mask-RT-DETR-X.yaml) | √ | √ |
| PaddleX | 实例分割 | [Mask-RT-DETR-S](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/instance_segmentation/Mask-RT-DETR-S.yaml) | √ | √ |
| PaddleX | 文本检测 | [PP-OCRv4_server_det](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_detection/PP-OCRv4_server_det.yaml) | √ | √ |
| PaddleX | 文本检测 | [PP-OCRv4_mobile_det](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_detection/PP-OCRv4_mobile_det.yaml) | √ | √ |
| PaddleX | 文本识别 | [PP-OCRv4_server_rec](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_recognition/PP-OCRv4_server_rec.yaml) | √ | √ |
| PaddleX | 文本识别 | [PP-OCRv4_mobile_rec](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_recognition/PP-OCRv4_mobile_rec.yaml) | √ | √ |
| PaddleX | 文本识别 | [ch_REPSVTR_rec](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_recognition/ch_RepSVTR_rec.yaml) | √ | √ |
| PaddleX | 文本识别 | [ch_SVTRv2_rec](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/text_recognition/ch_SVTRv2_rec.yaml) | √ | √ |
| PaddleX | 表格识别 | [SLANet](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/table_recognition/SLANet.yaml) | √ | √ |
| PaddleX | 版面分析 | [PicoDet_layout_1x](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/structure_analysis/PicoDet_layout_1x.yaml) | √ | √ |
| PaddleX | 版面分析 | [PicoDet-L_layout_3cls](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/structure_analysis/PicoDet-L_layout_3cls.yaml) | √ | √ |
| PaddleX | 版面分析 | [RT-DETR-H_layout_3cls](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/structure_analysis/RT-DETR-H_layout_3cls.yaml) | √ | √ |
| PaddleX | 版面分析 | [RT-DETR-H_layout_17cls](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/structure_analysis/RT-DETR-H_layout_17cls.yaml) | √ | √ |
| PaddleX | 时序预测 | [DLinear](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/DLinear.yaml) | √ | √ |
| PaddleX | 时序预测 | [RLinear](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/RLinear.yaml) | √ | √ |
| PaddleX | 时序预测 | [NLinear](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/NLinear.yaml) | √ | √ |
| PaddleX | 时序预测 | [TimesNet](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/TimesNet.yaml) | √ | √ |
| PaddleX | 时序预测 | [Nonstationary](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/Nonstationary.yaml) | √ | √ |
| PaddleX | 时序预测 | [TiDE](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_forecast/TiDE.yaml) | √ | √ |
| PaddleX | 时序异常检测 | [DLinear_ad](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_anomaly_detection/DLinear_ad.yaml) | √ | √ |
| PaddleX | 时序异常检测 | [PatchTST_ad](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_anomaly_detection/PatchTST_ad.yaml) | √ | √ |
| PaddleX | 时序异常检测 | [TimesNet_ad](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_anomaly_detection/TimesNet_ad.yaml) | √ | √ |
| PaddleX | 时序异常检测 | [Nonstationary_ad](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_anomaly_detection/Nonstationary_ad.yaml) | √ | √ |
| PaddleX | 时序异常检测 | [AutoEncoder_ad](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_anomaly_detection/AutoEncoder_ad.yaml) | √ | √ |
| PaddleX | 时序分类 | [TimesNet_cls](https://github.com/PaddlePaddle/PaddleX/blob/develop/paddlex/configs/ts_classification/TimesNet_cls.yaml) | √ | √ |
| PaddleNLP | 自然语言理解模型 | [BERT](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/legacy/model_zoo/bert) | √ | √ |
| PaddleNLP | 自然语言理解模型 | [ERNIE-3.0](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/legacy/model_zoo/ernie-3.0) | √ | √ |
| PaddleNLP | 自然语言理解模型 | [UIE](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/legacy/model_zoo/uie) | √ | √ |
| PaddleNLP | 自然语言理解模型 | [UTC](https://github.com/PaddlePaddle/PaddleNLP/tree/release/2.8/applications/zero_shot_text_classification) | √ | √ |
| PaddleNLP | 自然语言理解模型 | [RoBERTa](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/legacy/model_zoo/roberta) | √ | √ |
| PaddleNLP | 大语言模型 | [LLaMA](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/llm/npu/llama) | √ | √ |
