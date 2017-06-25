训练了人持匕首动作的识别。
训练环境为ubuntu16.04
下载后，darknet文件夹下，终端执行命令
./darknet detector test cfg/voc.data cfg/tiny-yolo-voc.cfg backup/tiny-yolo-voc_final.weights  图片路径
或识别视频
./darknet detector demo cfg/voc.data cfg/tiny-yolo-voc.cfg backup/tiny-yolo-voc_final.weights  视频路径
