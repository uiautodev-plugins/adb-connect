# adb-connect plugin for uiauto.dev

这个插件主要提供给uiautodev server端，可以暴露出ip:port，方便`adb connect`将设备连接到本地使用

## 安装

```sh
git clone https://github.com/uiautodev-plugins/adb-connect.git ~/.uiautodev/plugins/adb-connect
```

## 使用

- 启动uiautodev server端 <https://desktop.uiauto.dev>
- 选择Android设备进入，进入到插件Tab页
- 复制出来地址 eg: `adb connect 1.2.3.4:1234` 在本地的终端执行

# LICENSE

[MIT](LICENSE)
