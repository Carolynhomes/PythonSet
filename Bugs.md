# 1. import相关问题
## 1.1 import docx 的时候 报错
`No module named 'exceptions'`

[参考这篇文章](https://stackoverflow.com/questions/22765313/when-import-docx-in-python3-3-i-have-error-importerror-no-module-named-excepti)，说是`python 3.x `版本不适应这个，需要使用`python-docx `。

于是乎，执行`pip install python-docx `即可
