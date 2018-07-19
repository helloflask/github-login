# Github-Login
Example application for login with GitHub by GitHub-Flask

## Online Demo
https://helloflask.pythonanywhere.com

## Installation

```
$ git clone https://github.com/helloflask/github-login
$ cd github-login
```

## Register Your OAuth Application on GitHub

Go to https://github.com/settings/applications/new

Fill the form, then you will get your Client ID and Client Secret, write them into
app.py:

```python
app.config['GITHUB_CLIENT_ID'] = 'your_client_id'
app.config['GITHUB_CLIENT_SECRET'] = 'your_clent_secret'

```
*Warning: You normally need to save this values as enviroment variable in production.*

## Run

Just excute:
```
$ flask run
```
Then go to http://localhost:5000


# For Readers of Hello, Flask!

这个示例程序的介绍文章为[《使用GitHub-Flask实现GitHub第三方登录》](https://zhuanlan.zhihu.com/p/39026635)。
