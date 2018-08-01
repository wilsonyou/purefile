# 编译源代码

在成功安装依赖后才能编译BUMO的源代码。编译BUMO的源代码需要完成以下步骤：

  
1.在根目录下输入以下命令下载BUMO的源代码文件。如果没有安装git，可以通过`sudo apt-get install git`命令来安装git。

```
git clone https://github.com/bumoproject/bumo.git
```

![](/assets/download bumo_back2.png) 


**说明**：在BUMO的源代码下载过程中将自动创建bumo/目录，源代码文件将存放到该目录下。

  
2.输入以下命令进入到源代码的文件目录。

```
cd /bumo/build/
```

3.输入以下命令下载依赖并初始化开发环境。

```
./install-build-deps-linux.sh
```

4.输入以下命令回到bumo/目录下。

```
cd ../
```

5.输入以下命令完成BUMO源代码的编译。出现下图所示信息则表示编译成功。

```
make
```

![](/assets/compile_finished.png)  


**说明**：编译完成后生成的可执行文件**bumo** 和 **bumod** 存放在/bumo/bin目录下。

