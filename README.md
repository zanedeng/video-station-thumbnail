# video-station-Thumbnail

## 介绍

群晖Video Station自己搜集的视频经常没有缩略图

所以看到群晖的设置里有自动把与视频同名的图片文件作为缩略图的选项

就自己制作了这个镜像

## 使用说明

Docker上下载这个镜像

设置视频目录VOLUME为/video运行即可

自动在同名文件下创建缩略图（原图）

## 2.0版说明

1.0使用Python + opencv写的

2.0使用了纯ffmpeg 大幅度缩减镜像大小

同时纯shell命令行 努力学了一下午shell

和1.0同样的使用方式

## 贡献

务必Star！

欢迎Fork、PR！共同学习进步。
