# README.MD

本项目直接部署在阿里云服务器上，具体环境需求如下：

## 环境需求:

在以下环境中测试通过：

1. `ubuntu20.04`
2. `ubuntu18.04`

在ubuntu中，您可以使用该指令配置环境

```
apt-get install python
apt-get install build-essential
apt-get install libboost-all-dev
apt-get install libboost-dev
apt-get install python-pip
pip install -r deepcube/environment/requirements.txt -i https://mirrors.aliyun.com/pypi/simple/
```

## 1. 在服务器上部署服务

1. `cd deepcube/interface`
2. 执行 `python server.py`

## 2.测试

1. 见演示视频或访问`http://39.97.212.230:5000/`