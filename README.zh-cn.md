# kjson-for-python

这个模块是在 KJson 格式在 python 中的编解码器。

## 关于 KJson

KJson 是宽宽在[assist-2024](https://npmjs.org/package/@kuankuan/assist-2024)中定义的，基于 [json](https://www.json.org/) 的扩展格式。

KJson 最初致力于 JavaScript 语言的程序之间互相传输数据时类型安全等问题，保证了除 json 格式中定义的基本数据类型外，如日期等其他常用格式也被正常传输。

随着时间的推移，宽宽使用的技术栈、编程语言持续增加，慢慢的，KJson 也扩展到了其他编程语言中。

## 安装

```bash
pip install kjsonForPython
```

## 使用

```python
from kjsonForPython import KJson

KJson.stringify(...)
KJson.parse('...')
```

## 许可证

本项目使用[MulanPSL-2.0](LICENSE)许可证开源
