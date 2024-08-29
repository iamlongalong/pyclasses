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
