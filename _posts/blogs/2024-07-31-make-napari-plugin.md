---
layout: post
title: "Make napari plugin"
author: "Qiqi Lu"
category: blog
date: 2024-07-31
---

All done on Windows 11.

1. Create template and its GitHub repository using [napari-pluin-template](https://github.com/napari/napari-plugin-template?search=1). 

2. Code you own plugin using python.

3. Packaging you projects according to[ Packaging Python Projects](https://packaging.python.org/en/latest/tutorials/packaging-projects/#uploading-the-distribution-archives).

*May be you need to include `version` filed and delete `dynamic` filed to disable dynamic filed.*


Generating distributive archives [#](https://packaging.python.org/en/latest/tutorials/packaging-projects/#uploading-the-distribution-archives)

Make sure the latest version of PyPA's build installed:
```
python -m pip install --upgrade build
```

build
```
python -m build
```

This command should output a lot of text and once completed should generate two files in the dist directory:

```
dist/
├── xxx-0.0.1-py3-none-any.whl
└── xxx-0.0.1.tar.gz
```

Uploading the distribution archives

install Twine
```
python -m pip install --upgrade twine
```

run Twine to upload all of the archives under `dist`, the package will upload to https://pypi.org/ by default.

```
twine upload dist/*
```

Enter PyPI API token (press `Ctrol+Shift+V` to paste)
