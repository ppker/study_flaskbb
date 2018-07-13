# FlaskBB

[![Build Status](https://travis-ci.org/flaskbb/flaskbb.svg?branch=master)](https://travis-ci.org/flaskbb/flaskbb)
[![Coverage Status](https://coveralls.io/repos/sh4nks/flaskbb/badge.png)](https://coveralls.io/r/sh4nks/flaskbb)
[![Code Health](https://landscape.io/github/sh4nks/flaskbb/master/landscape.svg?style=flat)](https://landscape.io/github/sh4nks/flaskbb/master)
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](https://flaskbb.org)
[![flaskbb@freenode](https://img.shields.io/badge/irc.freenode.net-%23flaskbb-blue.svg)](https://webchat.freenode.net/?channels=flaskbb)

*FlaskBB is a Forum Software written in Python using the micro framework Flask.*

Currently, following features are implemented:

* Private Messages
* Admin Interface
* Group based permissions
* Markdown Support
* Topic Tracker
* Unread Topics/Forums
* i18n Support
* Completely Themeable
* Plugin System
* Command Line Interface

Feel free to checkout it's feature on our testing instance over at
[test.flaskbb.org](https://test.flaskbb.org). You can use the demo user (``demo//demo``) to
avoid the registration process.

The official forums where all the fun happens can be reached via [forums.flaskbb.org](https://forums.flaskbb.org).


## Quickstart

For a complete installation guide please visit the installation documentation
[here](https://flaskbb.readthedocs.org/en/latest/installation.html).

This is how you set up an development instance of FlaskBB:

* Create a virtualenv
* Configuration
    * `make devconfig`
* Install dependencies and FlaskBB
    * `make install`
* Run the development server
    * `make run`
* Visit [localhost:5000](http://localhost:5000)


## License

FlaskBB is licensed under the [BSD License](https://github.com/sh4nks/flaskbb/blob/master/LICENSE).


# Links

* [Project Website](https://flaskbb.org)
* [Documentation](https://flaskbb.readthedocs.io)
* [Source Code](https://github.com/sh4nks/flaskbb)


### 我总结的一些知识点
---
* bumpversion版本管理的一个python小工具
* Coverage是Python代码覆盖率分析工具,有关它的介绍和安装方法请见
* editorconfig 编辑器统一代码风格
* https://pypi.org python包的资源
* gitmodules 项目中使用了其他的git仓库资源，保持互相独立


