# pyclasses

pyclasses 用于生成 Python 代码的依赖图，可用于快速阅读一个项目。

# usage

```bash
## install
pip3 install pyclasses

## use
pyclasses /path/to/project file.svg [classname]
```

# develop

```bash
python3 setup.py sdist
twine upload dist/*
```

# info
其实用 `pyreverse -o svg -A -p langchain . ` 就挺好的
- 安装 `pip install pylint`

在 golang 中，使用 `[GoViz](https://github.com/hirokidaichi/goviz)` 能简约地看各个包的引用关系
使用 `[callvis](https://github.com/ondrajz/go-callvis)` 能比较容易看到类关系等等.
