## shell快捷键

### 1.控制命令

* <font color='red'> **Ctrl + l: 清屏（和clear命令效果相同）** </font>
* Ctrl + o：执行当前命令，并选择上一条命令
* Ctrl + s：阻止屏幕输出(当前正在执行的命令不在打印信息)
* Ctrl + q：允许屏幕输出(使用Ctrl+s命令后，可以用Ctrl+q恢复)
* <font color='red'> **Ctrl + c：终止当前正在执行的命令** </font>
* Ctrl + z：挂起命令，把当前进程转到后台运行，使用fg命令恢复。
* <font color='red'> **Ctrl + d : 退出当前 Shell ^S、^Q、^C、^Z 是由终端设备处理的，可用 stty 命令设置。** </font>





### 2.编辑命令

* <font color='red'> **Ctrl + a ：移到命令行首** </font>
* <font color='red'> **Ctrl + e ：移到命令行尾** </font>
* Ctrl + f ：前移（向右移动）一个字符
* Ctrl + b ：后退（向左移动）一个字符
* Alt + f ：前移（向右移动）一个单词
* Alt + b ：后退（向左移动）一个单词
* Ctrl + xx：在命令行首和光标之间移动





### 3.文本修改

* <font color='red'> **tab : 自动补全命令** </font>
* <font color='red'> **Ctrl + u ：从光标处删除至命令行首** </font>
* Ctrl + k ：从光标处删除至命令行尾
* Ctrl + w ：从光标处删除至字首
* Alt + d ：从光标处删除至字尾
* Ctrl + d ：删除光标处（或光标后）的字符（如果光标前后都没有字符，即命令行为空的时候，则会退出shell）
* Ctrl + h ：删除光标前的字符(与backspace键相同)
* Alt + Backspace：与 Ctrl + w 类似，分隔符有些差别
* Ctrl + y ：粘贴至光标后





### 4.改变大小写

* Alt + c ：从光标处更改为首字母大写的单词
* Alt + u ：从光标处更改为全部大写的单词
* Alt + l ：从光标处更改为全部小写的单词







### 5.**交换字符、单词位置**

* Ctrl + t ：交换光标处和之前的字符（ESC+t相同）
* Alt + t ：交换光标处和之前的单词





### 6.重新执行命令

* Ctrl + p：历史中的上一条命令
* Ctrl + n：历史中的下一条命令
* <font color='red'> **Alt + .：使用上一条命令的最后一个参数（会直接在当前光标位置显示）** </font>
* Ctrl + r：搜索之前使用过的命令
* Ctrl + g：从历史搜索模式退出

