## 命令行好用工具
* shell
  >Oh-My-Zsh ```zshell```是目前为止我使用颜值最高的shell,
  有很多可配置的功能，如果使用Git的话，会显示当前分支。
  吐槽一下，Mac的shell和linux的shell还是不太一样。
  特别是linux对于参数的位置一点不care,Mac
  还是延续Unix的风格，这点特别不爽~~
  ![zsh](https://ohmyz.sh/img/themes/daveverwer.jpg)

* 安装软件
  >Ubuntu下的```apt-get```用着超爽，其它linux版本也有类似工具
  Mac下```brew```感觉语法和```apt-get```差不都
  ```shell
  $ brew install bat
  ```
* 编辑器
  >当然是```vim```,完全不用鼠标就可以随心所欲的coding.
  特别是查找文本的效率特别快，如果用IDE,
  ```Ctrl+F```来回找烦死你
* bat
  >```cat```做的事情就是把文件内容打印出来，但是没有颜色高亮
  很不方便（没有颜色我基本看不懂代码 > <）。
  ```bat``` 不仅有颜色，还有行号、分页、加加减减的整合、
  类似 ```less``` 那样的搜索。
  建议在你的
  ![bat](https://www.kawabangga.com/wp-content/uploads/2018/09/bat-sample.png)
  **建议替换系统原有的cat**

  ```shell
  $ alias cat=bat
  ```
* prettyping
> ```ping```的替代物，看一下效果图
![prettyping](https://www.kawabangga.com/wp-content/uploads/2018/09/prettyping.gif)

  ```shell
  $ alias ping=prettyping
  ```
* htop
>```top```的替代物，```htop```提供的信息更明确，熟悉了快捷键效率
很高。比如按```P```按照**CPU**排序，```t```展示**树形**，```k```来
**kill**选中的进程等等
![htop](https://www.kawabangga.com/wp-content/uploads/2018/09/htop-1024x676.png)

* fd
> ```find``` 的语法太难记了，```fd```好用很多，显示还带高亮:
![fd](https://www.kawabangga.com/wp-content/uploads/2018/09/fd-1024x668.png)
