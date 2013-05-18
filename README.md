ShellStudy
==========

shell命令及shell编程笔记，徐徐更新。

######1. 如何为一个目录下的所有jpg图片文件添加文件名后缀，并将新的新图片保存在相同目录下？
for file in *.jpg; do cp "$file" "${file%.jpg}_suffix.jpg"; done

######2.
如何快速删除整个目录some_dir？
rm -rf some_dir , r stands for 'recursive', f stands for 'force'.
