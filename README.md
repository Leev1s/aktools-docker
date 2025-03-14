# aktools-docker

This repo is a auto builder for aktools docker image. Use default Dockerfile and update every night. The api will bind 0.0.0.0:8080 by default.

```shell
docker pull lev1s/aktools
```
```shell
# compose.yaml
version: "3.8"
services:
  aktools:
    container_name: aktools
    image: lev1s/aktools:latest
    ports:
      - 8080:8080
    network_mode: bridge
    restart: unless-stopped
```

[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/akshare.svg)](https://pypi.org/project/akshare/)
[![PyPI](https://img.shields.io/pypi/v/aktools.svg)](https://pypi.org/project/aktools/)
[![Downloads](https://pepy.tech/badge/aktools)](https://pepy.tech/project/aktools)
[![Documentation Status](https://readthedocs.org/projects/aktools/badge/)](https://aktools.akfamily.xyz/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![aktools](https://img.shields.io/badge/Data%20Science-AKShare-green)](https://github.com/akfamily/aktools)
[![Actions Status](https://github.com/akfamily/aktools/workflows/build/badge.svg)](https://github.com/akfamily/aktools/actions)
[![MIT Licence](https://img.shields.io/badge/license-MIT-blue)](https://github.com/akfamily/aktools/blob/master/LICENSE)
[![](https://img.shields.io/github/forks/akfamily/aktools)](https://github.com/akfamily/aktools)
[![](https://img.shields.io/github/stars/akfamily/aktools)](https://github.com/akfamily/aktools)
[![](https://img.shields.io/github/issues/akfamily/aktools)](https://github.com/akfamily/aktools)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

### AKTools

AKTools is a package of HTTP API for AKShare! It depends on AKShare, FastAPI and Typer.

[AKTools](https://github.com/akfamily/aktools) 是一款用于快速搭建 [AKShare](https://github.com/akfamily/akshare) HTTP API 的工具，通过 [AKTools](https://github.com/akfamily/aktools)
可以利用一行命令来启动 HTTP 服务，从而让原本专属服务于 Python 用户的开源财经数据接口库 [AKShare](https://github.com/akfamily/akshare) 的使用
突破编程语言的限制。无论您使用的是 C/C++、Java、Go、Rust、Ruby、PHP、JavaScript、R、Matlab、Stata 等编程语言或软件都可以快速、轻松获取财经数据，助力您更好地展开研究和开发工作。

**[AKTools 中文文档](https://aktools.readthedocs.io/)**


### Homepage

AKTools set a simple homepage for user to provide simple reference information. When you set up your
environment and deploy your local application, then you can type `http:127.0.0.1:8080` in your browser.
We are developing more functions now, please pay more attention!
