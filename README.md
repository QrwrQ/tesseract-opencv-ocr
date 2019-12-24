README

## 环境

linux系统（我用的是ubuntu16.04）

python3.5

下载tesseract

pakages: cv2,imutilsnumpy,pytesseract,argparse

如果是在我的系统的上用可以直接输入命令

```
source /home/roosi/ren/3ee/venv2/bin/activate
```

我已经建好的虚拟环境

## 使用

进入到项目目录中

```
cd /home/roosi/ren/ocropencv-text-recognition
python text_recognition.py --east frozen_east_text_detection.pb --image images/example_01.jpg
```

--images 后面是你要识别的图片

