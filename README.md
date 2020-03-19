# pdf2word

使用简单的python代码实现多线程PDF转Word，在win10 、python3.7 测试通过。 

目前仅能使用纯文本的读取，无法识别pdf的图片。

## 使用方法

* clone或下载项目到本地
```python
git clone git@github.com:leebeep/pdf_to_word.git 
```

* 进入项目目录，建立虚拟环境，并安装依赖。

```python
cd pdf2word
python -m venv venv  
source venv/bin/activate
pip install -r requirements.txt
```

* 修改config.cfg文件，指定存放pdf和word文件的文件夹，以及同时工作的进程数

* 执行```python main.py```

## License

采用 MIT 开源许可证
