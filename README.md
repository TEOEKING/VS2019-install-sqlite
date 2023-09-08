# Windows通过vcpkg安装sqlite3,使Visual Studio可以使用其库函数
记录一下通过微软提供的vcpkg来安装其库文件，**https://vcpkg.io/en/getting-started**
## 1.下载vcpkg-master.zip
首先访问到由于此时我的win电脑没有安装git，所以我访问到了**https://github.com/Microsoft/vcpkg.git** ,直接将右上角的文件下载了下来
## 2.解压vcpkg-master.zip文件
将下载好的文件移动到D:\Microsoft Visual Studio，新建了一个名为Tools的文件夹，然后解压**vcpkg-master**
## 3.进入到vcpkg-master文件中 运行下列代码
    .\vcpkg\bootstrap-vcpkg.bat
    vcpkg install sqlite3
再打开VS，弹出提示进行配置安装即可
