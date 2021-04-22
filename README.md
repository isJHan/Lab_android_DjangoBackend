python == 3.9.2

```shell
> python -m venv venv # 初始化虚拟环境
> ./venv/Scripts/activate # 启动虚拟环境
# 如果在Linux请替换为下面的代码
# > source ./venv/bin/activate
(venv)> pip install -r ./requirements.txt # 安装依赖包
(venv)> python ./demo0/manage.py runserver # 启动项目



```

如果要退出虚拟环境执行`deactivate`

### P.s. 
1. (在Linux上安装多个python版本CSDN)[https://blog.csdn.net/qq_38208506/article/details/104777516]
2. 在初始化虚拟环境时, 将python替换为想要创建venv的python版本号(python3以上)


