1. 在Notebook中打开新的文件夹
  找到右上角 New → Terminal
 cd 根路径
 jupyter notebook

2. 将已经存在的conda环境注册到Jupyter Notebook
 conda activate 环境名称 （激活环境）
  python -m pip install ipykernel （安装Jupyter内核，没有Jupyter内核的才需要安装）
 python -m ipykernel install --user --name 内核内部名称 --display-name "Python (内核内部名称)"

 