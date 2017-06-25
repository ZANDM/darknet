训练了人持匕首动作的识别。
训练环境为ubuntu16.04
下载后，darknet文件夹下，终端执行命令
./darknet detector test cfg/voc.data cfg/tiny-yolo-voc.cfg backup/tiny-yolo-voc_final.weights  图片路径
或识别视频
./darknet detector demo cfg/voc.data cfg/tiny-yolo-voc.cfg backup/tiny-yolo-voc_final.weights  视频路径




特别的。需要修改cfg/voc.data 文件中的路径，改为自己本机的路径。
如，
train  = /home/zandm/darknet/scripts/2007_train.txt
将"zandm"指你的用户名。你需要将"darknet"前的路径改为适应你本机。

