http://blog.cofface.com/archives/741.html

支持windows下打包boot/recovery.img的bootimg.exe，且支持自动解包/打包dt.img,加入MTK机型支持
点击量:19877次 作者:cofface
2014.04.20

目前新的高通机型boot.img或recovery.img解包后均带有dt.img，旧版的bootimg.exe无法支持。

更新日志：

20140420:

加入MTK机型支持

bootimg.exe功能：

解包命令：bootimg.exe –unpack-bootimg      

打包命令：bootimg.exe –repack-bootimg   

recovery/boot文件放到bootimg.exe同一级目录即可。

更多命令：

–add-head
–cml
–cpio-list
–czlib
–dml
–dzlib
–remove-head
–repack-565
–repack-bootimg
–repack-ramdisk
–repack-rle
–repack-zte-bin
–rml
–to-ext4
–to-img
–uml
–unpack-565
–unpack-bootimg
–unpack-qsb
–unpack-ramdisk
–unpack-rle
–unpack-updata
–unpack-yafffs
–unpack-yaffs
–unpack-yaffs2
–unpack-zte-bin

1 2 3 4

 

下载地址：链接: http://pan.baidu.com/s/1bn2c6n1 密码: thns