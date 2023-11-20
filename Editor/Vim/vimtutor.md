## 移动光标
h `<left>`、 j`<down>`、 k`<up>`、 l`<right>`


## 退出 vim
normal模式下：<Br />
输入 `:q!` 放弃所有更改退出<Br />
输入 `:wq` 保存退出

## 文本编辑

`x` 删除光标下的字符<Br />

### 插入模式
输入 `i` 在光标处插入<Br />
输入 `A` 在整行后面拼接输入

## 删除命令

> `d motion` 模式 motion 是具体的动作行为<Br />

`dw` 删除单词<Br />
`de` 删除光标位置开始到单词结束<Br />
`d$` 删除光标后至行尾<Br />
`dd` 删除整行

## 数字 motion

`2w` 跳转光标定位至 2 个单词后的单词首字母<Br />
`3e` 跳转光标定位至 3 个单词后的单词尾字母<Br />
`0` 跳转至行首字符位置

> d number motion

`d2w` 删除两个单词
`2dd` 删除两行

## 撤销操作

`u` 撤销最后一次命令操作，`U` 恢复整行修改; `Ctrl R` 恢复撤销操作