# MMDetection3D
## 简介
您可以使用open-mmlab开源的mmdetection3d来训练融合算法和激光雷达检测算法。

## 训练与测试

1. 下载数据集，并解压至以下目录结构

   ```shell
   ├── train
       ├── scene0
           ├── DumpSettings.json
           ├── image
           ├── image_label
       ...
   ├── test
       ├── scene1
           ├── DumpSettings.json
           ├── image
       ...
   ```

2. 运行开发工具提供的脚本生成kitti格式的数据集

   ```python
   python simone2kitti.py
   ```

   

3. 根据mmdet3d的介绍配置换环境和训练算法，mmdetection3d的链接如下
    ```
    https://github.com/open-mmlab/mmdetection3d
    ```

## Credit

```
https://github.com/open-mmlab/mmdetection3d
```

