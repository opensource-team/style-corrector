# style-corrector
An automated docx file style-corrector, implemented by python.

许多办公室工作者的一项重要而又枯燥的工作是校对文稿的格式。我们因此希望设计一个可以改正指定文件夹及其子文件夹中所有office docx文件字体及段落格式的程序，用python实现。文稿格式将被改为预设的规范的格式，例如投行对于募集说明书的要求：中文小四宋体，英文及数字小四times new roman，表格字体五号居中，段落间距为1.5倍，段前段后间距各0.5行等等。

我们将该工作分为两个部分：设计算法以及设计GUI。最后我们希望将结果打包成exe程序，使之可以在广受普罗大众欢迎的Windows系统运行。

过程中使用到的package：
python-docx 负责处理docx文件
os 处理文件路径相关事
tkinter 用于搭建GUI

