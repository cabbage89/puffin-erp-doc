### 预览
```
# windows
docker run --rm -it -p 52432:8000 -v "%cd%":/docs squidfunk/mkdocs-material

# linux/mac
docker run --rm -it -p 52432:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

[mkdocs文档](https://squidfunk.github.io/mkdocs-material/creating-your-site/)

### 创建

```
docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
```