# 目前仅支持 CC 系列的工具，旧版不再支持，如出现不可用，请前往 [https://app.yaozuopan.top](https://app.yaozuopan.top) 下载最新版

# CodeMixer
在H5游戏项目中需要添加垃圾代码作混淆，提高过审机率。手动添加太费时费力，在网上并没有找到合适的比较好的工具，就自己动手写了一个垃圾代码添加工具，命名为ChaosTool，CodeMixer是ChaosTool增强版

## [ [官网](https://www.me88.top/index.php/158.html) ]

## CodeMixer安装环境
- macOS 10.12+ (不支持Windows)

## CodeMixer介绍
ChaosTool升级版，完全重构，更多新功能，再也不是乱码，有以下特点

| 功能 | ChaosTool | CodeMixer |
| :---- | :-------: | :------: |
| 自动定义变量/函数/属性 | 支持 | 支持 |
| 自动实现函数体 | 支持 | 支持 |
| 自动创建/并编写类文件(.h/.m) | 支持 | 支持 |
| 自动创建文件夹 | 支持 | 支持 |
| 自动备份原始代码 | `不支持` | 支持 |
| 离线授权认证 | `不支持` | 支持 |
| 变量/参数/函数返回/属性类型支持UIKit | `不支持` | 支持 |
| 变量/参数/函数返回/属性支持自己创建的类 | `不支持` | 支持 |
| 允许添加方法前缀 | `不支持` | 支持 |
| 允许修改类名/文件名前缀 | `不支持` | 支持 |
| 创建Model | `不支持` | 支持 |
| 创建View | `不支持` | 支持 |
| 创建ViewController | `不支持` | 支持 |
|  允许修改署名和版权归属(对于新建文件) | `不支持` | 支持 |
| 实现相对复杂的方法体 | `不支持` | 支持 |
| 代码规则化 | `不支持` | 支持 |
| 代码相互调用 | `不支持` | 支持 |
| 允许用户定制单词库 | `不支持` | 支持 |
| 其他功能:批量修改类名、批量修改图片MD5 | `不支持` | 支持 |

CodeMixer创建文件示例(定义文件)
![](https://www.yaozuopan.top/usr/uploads/2019/01/593942023.jpg)
`不要怀疑，这真不是人写的，这真不是人写的，这真不是人写的`

CodeMixer创建文件示例(实现文件)
![](https://www.yaozuopan.top/usr/uploads/2019/01/2978580583.jpg)
`不要怀疑，这真不是人写的，这真不是人写的，这真不是人写的`

CodeMixer添加垃圾代码示例(实现文件)
![](https://www.yaozuopan.top/usr/uploads/2019/01/2185348302.jpg)
`不要怀疑，这真不是人写的，这真不是人写的，这真不是人写的`

## CodeMixer三大功能
### 1、混淆
向项目添加混淆/垃圾代码
![](https://www.yaozuopan.top/usr/uploads/2019/01/896244946.jpg)

#### 路径
选择一个目录(只能是目录)，表示对该目录下所有所有OC(.m、.mm、.h)文件操作

#### 操作完成后要做
- 添加以下文件及目录到项目中
![](https://www.yaozuopan.top/usr/uploads/2019/01/677581964.jpg)
- 引用代码
![](https://www.yaozuopan.top/usr/uploads/2019/01/2480507536.jpg)
`注意：` **HH**为前缀，实际要替换成你自己的前缀(`在设置选项查看`)

#### 单词库
可以自定义自己的单词库，覆盖默认单词库。
`规则`
1、单个词，全为小写
2、组合单词，从第二个单词起，首字母为大写
例如1：userAction,adminAction,loginManger
例如2：adminLoginAccess,userLoginAccess, normalLogoutAccess
依此类推
3、用英文逗号连接
举例：people,user,userAction,login,userLoginAccess,loginManger


### 2、类名
批量修改类名
![](https://www.yaozuopan.top/usr/uploads/2019/01/2024172414.jpg)

#### 路径
选择一个目录(只能是目录),表示对访目录所有OC文件(.h、.m、.mm)中的NSObject的子类的类名进行更改
执行解析操作后，就开始解析类名，完成出现如下界面
![](https://www.yaozuopan.top/usr/uploads/2019/01/975103611.jpg)

在此界面可以修改自己钟意的新类名，以替换原始类名

`执行修改`操作就开始进行替换,不能撤消

### 3、图片(支持png、jpg)
批量处理图片
- 微调(用于改变图片MD5,图片尺寸会改变，比例不变)
- 2倍图转1倍图(将源图片作为2倍图，批处理成1倍图，例如源图片为: 100px X 40px, 处理后为: 50px X 20px)
- 2倍图转3倍图(将源图片作为2倍图，批处理成3倍图，例如源图片为: 100px X 40px, 处理后为: 150px X 60px)
- 3倍图转1倍图(将源图片作为3倍图，批处理成1倍图，例如源图片为: 90px X 60px, 处理后为: 30px X 20px)
- 3倍图转2倍图(将源图片作为3倍图，批处理成2倍图，例如源图片为: 90px X 60px, 处理后为: 60px X 40px)

![](https://www.yaozuopan.top/usr/uploads/2019/01/2337809516.jpg)
#### 路径
选择一个目录(只能是目录),表示对访目录所有png/jpg文件进行处理
