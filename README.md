# xiaoqidao_wyclx

## **介绍**
这是一个用于网易游戏《一梦江湖》的挂机脚本。该脚本使用Python编写，图形用户界面（GUI）使用PyQt5，图像识别和模拟点击使用Airtest和pywin32。

## **功能**
1. 自动采集（目前为半成品）

## **预览图**
![image]([https://i.328888.xyz/2023/02/03/NfPAy.png](https://github.com/xiaoqidaov2/wyymjh_script/blob/master/%E6%8D%95%E8%8E%B7.PNG?raw=true))

## **注意事项**
1. 确保应用以“管理员身份运行”，否则应用将无法嵌入到脚本界面中。

## **项目结构**
```
xiaoqidao_wyclx/
├── main.py
├── caiji_thread.py
├── gui.py
├── image_resources.py
└── utils.py
```

### **文件说明**
- **main.py**：主程序入口，负责启动应用程序。
- **caiji_thread.py**：自动采集线程模块，包含自动采集的主要逻辑。
- **gui.py**：图形用户界面模块，包含应用的界面设计和用户交互逻辑。
- **image_resources.py**：图像资源模块，存储用于图像识别的图像数据。
- **utils.py**：工具模块，包含一些辅助函数，如模拟点击和删除图像文件。

## **安装与运行**
### **依赖安装**
在运行脚本之前，请确保安装了以下依赖：
```bash
pip install PyQt5
pip install airtest
pip install pywin32
```

### **运行脚本**
1. 下载或克隆本项目到本地。
2. 以管理员身份运行命令提示符或终端。
3. 导航到项目目录并运行以下命令：
```bash
python main.py
```

## **使用说明**
1. 启动脚本后，会显示一个窗口，嵌入了游戏界面。
2. 点击“开始采集”按钮，脚本会开始自动采集。
3. 点击“停止采集”按钮，可以随时停止自动采集。
