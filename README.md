## 本项目用于存放兰剑云项目的proto文件  
在目录下为不同目录创建

1. 拉取文件  
   go get github.com/hby07/lanjian-protofile  
2. 在goland中自定义protofile文件路径，否则编辑器无法识别要导入的文件。  
   File--》Settings--》Languages&Frameworks--》Protocol Buffers
   取消自动配置，点击加号添加protofile所在路径，通常可以添加{GO_PATH}/pkg/mod