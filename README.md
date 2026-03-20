# Python 视觉开发环境搭建与图像基本读写实验

## 一、项目概述
本项目是计算机视觉入门实验，基于 Python + OpenCV + NumPy + Matplotlib 实现图像的读取、信息查看、灰度转换、显示、保存及像素操作。通过本次实验熟悉图像处理基本流程，掌握 Git 项目提交规范。

## 二、技术栈
- Python 3.x
- OpenCV-Python
- NumPy
- Matplotlib

## 三、文件清单
- main.py        实验主程序代码
- test.jpg       测试图片
- gray_test.jpg  生成的灰度图
- crop_test.jpg  裁剪后的图片
- README.md      项目说明文档

## 四、环境配置
安装依赖库：
pip install opencv-python numpy matplotlib

## 五、运行步骤
1. 将代码与 test.jpg 放在同一目录
2. 运行 main.py
3. 查看控制台输出与弹出的图像窗口
4. 查看生成的灰度图与裁剪图

## 六、核心功能解析
1. 图像读取：使用 cv2.imread 读取图片并判断是否为空
2. 图像信息输出：打印宽度、高度、通道数、数据类型
3. 格式转换：BGR 转 RGB，解决 Matplotlib 颜色显示异常
4. 灰度图转换：使用 cv2.COLOR_BGR2GRAY
5. 图像保存：保存处理后的图片到本地
6. NumPy 操作：获取指定像素值、图像区域裁剪

## 七、作业总结
本次实验完成了图像读取、信息输出、彩色转灰度、图像保存、像素访问与裁剪等任务。理解了 OpenCV 的 BGR 格式与 Matplotlib 的 RGB 格式差异，掌握了基本的图像数组操作方法，能够熟练使用 Git 提交项目文件。