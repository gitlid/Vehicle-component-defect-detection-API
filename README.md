# 车辆零部件缺陷检测API

## 简介
为车辆零部件缺陷检测提供API服务。

## 安装步骤
下载release内的压缩包解压即可使用

# 安装依赖
无需安装依赖，直接运行可执行文件

## 使用方法
说明如何使用项目，提供示例代码或命令：# 示例代码
cd fastapi_gpu_CTRS2 # 进入项目目录

fastapi_gpu_CTRS2.exe -h # 查看使用帮助
usage: fastapi_gpu_CTRS2.exe [-h] [--workers WORKERS] port model

positional arguments:
  port               端口号
  model              YOLO模型文件路径

options:
  -h, --help         show this help message and exit
  --workers WORKERS  工作进程数

服务启动输入样例
fastapi_gpu_CTRS2.exe 10195 NEU-DET.pt

# 使用模块中的函数
result = your_module.your_function()
print(result)

## 目录结构
展示项目的主要目录结构：
fastapi_gpu_CTRS2/
├── _internal/
│   └── 各类依赖库
└── fastapi_gpu_CTRS2.exe
    
