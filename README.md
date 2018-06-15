# word_cup_2018
2018世界杯热门分析


#### python2.7 安装：

    下载：https://www.python.org/downloads/
    
    环境变量：D:\Python27;D:\Python27\Scripts
    
  
#### pip是python的安装源

   安装：https://pypi.org/project/pip/#files
   
   解压；
   
   cd 到解压后的目录：python setup.py install
   
   然后验证pip是否安装成功；
   
   修改默认配置： 在文件夹中数据 %APPDATA%
   
   新建文件夹pip 新建pip.ini
```             
 [global]  
index-url = http://pypi.douban.com/simple #豆瓣源，可以换成其他的源  
trusted-host = pypi.douban.com            #添加豆瓣源为可信主机，要不然可能报错  
disable-pip-version-check = true          #取消pip版本检查，排除每次都报最新的pip  
timeout = 120              
```

Jupyter notebook: Jupyter Notebook（此前被称为 IPython notebook）是一个交互式笔记本，支持运行 40 多种编程语言.

安装 jupyter: pip install jupyter

运行 jupyter notebook

#### pandas使用
參考：http://www.codingpy.com/article/use-pandas-for-data-analysis-one/
http://www.codingpy.com/article/a-quick-intro-to-pandas/
