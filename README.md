# face_recognition
基于虹软的人脸识别项目

   1. 人脸识别项目 
       项目目录：/usr/projects/faceRecognitionProject
       项目配置：/usr/projects/faceRecognitionProject/config/faceRecognitionFile (虹软人脸识别的.so结尾的linux系统文件，静态文件在springboot中需要配置绝对路径,目录是/usr/projects/faceRecognitionProject/config/faceRecognitionFile)
       项目访问路径：http://www.jljinqilong.cn (80端口),      https://www.jljinqilong.cn:433 
       注意：由于人脸识别项目需要开启摄像头，开启摄像头操作必须是https协议才支持，所以项目http协议请求方式会重定向到https协议请求方式(项目中代码实现)
