# Markdown编辑阅读器使用

标签（空格分隔）： 想砸电脑的Hexo安装过程
本想一起完成**Markdown**作业和个人博客的作业，但无奈**Hexo**死活装不上。其安装过程如下：
>  安装前准备github账号、git、node.js
### 1. github创建仓库
> * Github注册
> * 创建仓库：用户名.github.io

done
### 2. 安装git
> * 官方下载地址https://pages.github.com/
> * 安装步骤：双击下载好的exe文件，一路next就好啦
> * 安装好后，打开gitbash，查看版本，命令：`$git --version`

done

### 3. 安装nodejs
> Hexo是基于nodeJS环境的静态博客，因此需要安装nodejs，npm是nodejs中很有用的工具，现在nodejs版本中都集成了npm。

> * nodejs下载地址https://nodejs.org/en/(说明：LTS为长期支持版，Current为当前最新版)
> * 安装步骤：反正下载好msi文件后，双击打开安装，也是一路next，不过在Custom Setup这一步记得选 `Add to PATH` ,这样你就不用自己去配置电脑上环境变量了，装完在按 `win + r` 快捷键调出运行，然后输入cmd确定，在cmd中输入path可以看到你的node是否配置在里面（环境变量），没有的话你就自由发挥吧。
> * 查看版本,命令：`$node -v`

done

### 4.安装Hexo
前面的安装都完成了，就差最后一步了，没错**Hexo**官方安装：`$ npm install -g hexo-cli`就这一步，似不似很简单。。。。。
然后我输入后，回车，光标一直闪烁，马丹，你不安装成功，你倒是给我报错啊aaaaaaa。

####1.nodesjs版本问题？
| nodejs     | 版本   |  
| --------   | :-----:  | 
|   nodejs  | node-v6.11.2-x64.msi |
|   nodejs   | node-v8.2.1-x64.msi |

oh,yeah,不是

####2.国外/公司限制下载过慢？
没得事，我们有taobao镜像
`$ npm install -g cnpm --registry=https://registry.npm.taobao.org`

你动啊，你倒是动啊aaaaaaaaaaaa
`i done`。

---





