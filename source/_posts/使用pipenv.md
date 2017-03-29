---
title: 使用pipenv
date: 2017-02-26 08:40:35
tags: python, virtualenv
---

## pipenv

管理 virtual environment 一直是 Python 使用者比较头疼的问题，当然为了解决这个痛点，很多优秀的项目也涌现了出来，也取得了很多的用户群体，比如 `pyvenv`、`virtualwrapper`等，不过最近 [kennethreitz](https://github.com/kennethreitz)发布了一个新的虚拟环境工具,就是标题提到的 `pipenv`,作为k神的拥趸，一定要支持一下的

> Pipenv is an experimental project that aims to bring the best of all packaging worlds to the Python world.

## 安装

项目地址： [https://github.com/kennethreitz/pipenv](https://github.com/kennethreitz/pipenv)

DOC地址： [http://docs.pipenv.org/en/latest/](http://docs.pipenv.org/en/latest/)

```bash
$ curl https://raw.githubusercontent.com/mitsuhiko/pipsi/master/get-pipsi.py | python

$ pipsi install pew
$ pipsi install pipenv

$ pipsi upgrade pipenv
```

下面是猜想的简单的安装方法 大家可以试试

```bash
$ pip install pipenv
```

## 使用方法

使用非常简单， DOC 上也有图解

```bash
$ pipenv --three / --two  Use Python 3/2 when creating virtualenv.
$ pipenv install package
$ pipenv lock
$ pipenv shell
$ pipenv freeze
```
