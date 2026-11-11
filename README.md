# obscurepawn.github.io

“平安成电智慧通行”界面的静态页面源码，由 HTML、CSS、JavaScript 和图片组成。仓库没有服务端工程，也不需要前端构建工具。

## 本地查看

安装 Git 和 Python 3 后运行：

```sh
git clone https://github.com/Obscurepawn/obscurepawn.github.io.git
cd obscurepawn.github.io
python3 -m http.server 8000 --bind 127.0.0.1
```

在浏览器打开 [本地首页](http://127.0.0.1:8000/)，按 `Ctrl+C` 停止服务。

## 文件入口

| 路径 | 内容 |
| --- | --- |
| [index.html](index.html) | 默认首页 |
| [genQrode.html](genQrode.html) | 行人二维码展示页面 |
| [personPassRule.html](personPassRule.html) | 通行规则页面 |
| [_index.html](_index.html) | 带信息输入表单的另一份首页，不是默认入口 |
| [scripts/](scripts/) | 页面交互脚本 |
| [files/](files/) | 本地样式、图片和脚本资源 |

页面展示由浏览器脚本完成，仓库不包含身份认证或通行授权服务。部分资源仍引用 `smaco2.uestc.edu.cn`；离线或外部资源不可用时，页面显示可能不完整。

