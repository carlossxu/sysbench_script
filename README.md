# sysbench_script
在本地运行sysbench然后将性能指标输出到excel文件中

需要安装openpyxl和sysbench

```
pip install openpyxl

yum install -y sysbench
```

使用方法：
```
python3 benchmark.py cpu/mem/fileio
```
运行完成后，会在当前目录下创建result目录，里面存放了每次运行的结果文件。并且在当前目录下生成测试结果的excel文件
