#cd /usr/share/vim/vimfiles/
#cp /root/doc/* doc/
#cp /root/plugin/* plugin/
yum install ctags
===========================
 打开.c文件，按esc键进入normal状态下，直接输入“wm”（这儿一定注意不是在命令行中输入：wm）
 
 ---------------将vim别名更改为为vi-----------------------------
echo "alias vi='vim'" >>/etc/profile
tail -l /etc/profile
source /etc/profile
