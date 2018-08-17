# MkDocs

- 2018/08/17
- [MkDoc官網](https://www.mkdocs.org/) - 用來架文件 Server


## Prepare

```sh
$ pip install mkdocs
$ python -m pip install --upgrade pip
```


## Use

```sh
# Use
$ mkdocs new my-project
INFO    -  Creating project directory: my-project
INFO    -  Writing config file: my-project\mkdocs.yml
INFO    -  Writing initial docs: my-project\docs\index.md

$ cd my-project

$ mkdocs serve
```



# mkdocs.yml 組態檔

```yml
site_name: My QQ            # 頁面左上角 標題
pages:
    - Home: index.md
    - About: about.md
theme: readthedocs          # 頁面風格
```


## 頁面 icon

專案架構

```sh
/my-project
    /docs
        /img        # icon放這邊
    index.md
    mkdocs.yml
```



# 架站~~

```sh
$ cd my-project
$ mkdocs build
# 建立 site (一整包阿~~)
```