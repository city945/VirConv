##### VirConv

* 知识点

  * `new_p: xyz0 rgb 1 ;new_lidar: xyzi 000 2; 1 为虚拟点，2为激光点`
* 代码运行

  * 环境配置

    * `city945/cuda11.3-python3.8-pytorch1.11-devel`

      * `pip install prefetch_generator `
  * 数据集准备
  * 快速入门

    * ```bash
      # 深度补全生成 velodyne_depth (修改 vis_utils.py 以生成图像的深度文件 image_2_depth)
      python3 main.py --detpath ../../data/kitti/training -e ../../model_zoo/download/pe.pth.tar
      ```
* 代码阅读 Github

  *