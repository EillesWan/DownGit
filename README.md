<h1> <img src="https://github.com/EillesWan/DownGit/raw/master/res/images/downgit.png" width="20" height=auto /> DownGit </h1>

<!-- [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate/?business=5KR6BA9MYTM62&no_recurring=0&currency_code=USD) -->

#### 通过目录链接下载 GitHub 资源

通过此工具，您可直接下载任何 GitHub **公共仓库之目录或文件**，或取得其下载链接。

### 站点

[原作者之 DownGit](https://minhaskamal.github.io/DownGit)

[鄙人之贱 Fork](https://eilleswan.github.io/DownGit)

### 用法

<table><tr><td> <img src="https://cloud.githubusercontent.com/assets/5456665/17822364/940bded8-6678-11e6-9603-b84d75bccec1.gif" /> </td></tr></table>

1. 前去上述链接地址
2. 输入 GitHub 仓库链接
3. 你可以下载或者获取链接
    - 获取链接的话，就可以随意使用这个链接地址了\
      例如把它输入到浏览器地址栏，然后回车即可下载
4. 当然也可以直接下载，只需数秒即可保存了

##### 高级用法

获取的链接，最经典的应该很像这种：

```
https://eilleswan.github.io/DownGit/#/home?url=<GitHub链接>&fileName=<文件名称>&rootDirectory=<true 或 false 或 名称>
```

OK，假设你需要以 **`DownGit-Images.zip`** 作为下载文件名，来下载 **`https://github.com/MinhasKamal/DownGit/tree/master/res/images`**，顺便带上 **`ImagesOfDownGit`** 作为根目录之名称，那么下载链接将会是

```
https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/tree/master/res/images&fileName=DownGit-Images&rootDirectory=ImagesOfDownGit
```

默认情况下，参数 `fileName` 及 `rootDirectory` 是你原本下载的文件或文件夹的名字。如果你不想要把文件夹本身包入下载的压缩包里，你可以设置 `rootDirectory=false`。例如这个链接

```
https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/tree/master/res/images&rootDirectory=false
```

就会下载一个名字叫 **`images.zip`** 的压缩包，且其根目录 `"images"` 将不被包含其中。

下载文件的话，例如这个 **`https://github.com/MinhasKamal/DownGit/blob/master/res/images/downgit.png`** 和这个而名字 **`DownGitIcon.zip`**，那就可以给出这样的下载链接

```
https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/MinhasKamal/DownGit/blob/master/res/images/downgit.png&fileName=DownGitIcon
```

### 协议

<a rel="license" href="https://opensource.org/licenses/MIT"><img alt="MIT License" src="https://cloud.githubusercontent.com/assets/5456665/18950087/fbe0681a-865f-11e6-9552-e59d038d5913.png" width="60em" height=auto/></a><br/><a href="https://github.com/MinhasKamal/DownGit">DownGit</a> is licensed under <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
