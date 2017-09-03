# Django 项目模板

* [x] 使用新的目录结构
* [x] 所有文件使用 UTF-8 编码，使用 `\n` 作为行分隔符
* [x] 修改默认配置，适合中国
* [x] 使用 django-environ 重构配置文件
* [x] 使用 django-extensions
* [x] 使用 django-debug-toolbar

## 项目布局

* `<project>`
  * `<static>`
  * `<templates>`
    * `404.html`
    * `500.html`
    * `base.html`
  * `__init__.py`
  * `settings.py`
  * `urls.py`
  * `wsgi.py`
* `.env`
* `manage.py`
* `requirements.txt`

## .env 文件

参考： http://django-environ.readthedocs.io

注意事项:

* 环境变量名允许字母、数字、下划线
* 严格符合 `ENVIRON_VARIABLE_NAME=VALUE` 的行才生效，`=` 左边不能有空格
* 不符规范的行会静悄悄的忽略掉，因此可用作注释行

示例，参见 .env 文件
