<center> Git Summary </center>
===============
<center> Xuntian Wang </center>



> ## Chapter 1. Get Start. ##

> 1. 在 Linux 中安装Git：
>
>         $ sudo yum install git

> 2. 配置 Git：
>     
>     * 读写配置变量：
>
>           $ git congif 
>
>     * 完善用户信息 (Run for only once):
>
>           $ git config --global user.name "John Doe"
>           $ git config --global user.email johndoe@example.com
>
>     * 设置文本编辑器 (若未安装， 请百度）：
>
>           $ git config --global core.editor visual studio code
>
>     * 检查配置信息:
>
>           $ git config --list
>
>     * 检查 Git 的某一项配置:
>
>           $ git config user.name

> 3. 获取帮助
>
>     * 3种不同的命令语句：
>
>           $ git help <verb>
>
>           $ git <verb> --help
>
>           $ man git-<verb>
>
>     * 举例：
>           $ git help config



> ## Chapter 2. Obtain Git Repository. ##

> 1. 创建本地根目录：
>
>     * 方法一：手动创建（新建文件夹）；返回编译器；输入 cd 语句
>     
>           $ cd D:/learngit
>
>     * 方法二：使用命令行，直接在编译器中输入 mkdir 语句
>           $ mkdir LearnGit
>
>







> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

*   A list item with a blockquote:

    > This is a blockquote

    > inside a list item.

如果要放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符：



