首先将Emacs Setting 文件夹解压，将samuel_emacs文件重名为.emacs,然后将其放入/home/yourusername/下。

然后将_emacs.d.tar.gz解压重命名为.emacs.d放之于/home/yourusrname/  

清空home/yourusername/.emacs.d/lisps/_emacs/install里面的内容，保留文件夹


安装yasnippet：(模板功能)
在~/home/yourusername/.emacs.d/lisps/_emacs/install目录下解压

安装auto-complete:(自动补全)
在~/home/yourusername/.emacs.d/lisps/_emacs/install目录下 tar 解压,然后make(该文件夹不能被移动)

安装cedet:
在~/home/yourusername/.emacs.d/lisps/_emacs/install解压,然后看INSTALL安装。

安装ecb:
在~/home/yourusername/.emacs.d/lisps/_emacs/install 里解压


注：为了更好的使用，请看samuel_emacs文件base.el 和以cy开头的文件

base.el中存放emacs基本设置
cycode.el中存放coding相关的设置
cyexpand.el中存放emacs扩展配置设置
addon.el配置可以改变emacs更像IDE，不过奇丑无比，慎用
cykbd.el存放键绑定设置，好用
