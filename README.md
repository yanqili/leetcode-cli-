# leetcode-cli-
## ubuntu 下安装注意事项
1、打开安装指导网页https://skygragon.github.io/leetcode-cli/install.html

2、该网页中有多种安装方式，本人最终用的from github 的方式安装成功
```
$ npm install -g skygragon/leetcode-cli
```

3、若安装失败，提示是npm的问题，则依次尝试了如下方法，才成功解决。
```
$ npm cache clean 失败
```

```
$ npm cache clean --force 失败
```

```
$ npm cache clear --force && npm install --no-shrinkwrap --update-binary 成功
```
4、npm没问题后，安装leetcode-cli 还是有问题，仔细看了一下是没给权限，然后就安装成功了。
```
$ sudo npm install -g skygragon/leetcode-cli
```


