# MyARouterTest
使用阿里Arouter路由实现模块化开发简介<br>
来自于<br>
https://blog.csdn.net/huangxiaoguo1/article/details/78753555 <br>
https://download.csdn.net/download/huangxiaoguo1/10151401 <br>
收藏学习使用。<br>
对于 <br>
```
annotationProcessor "com.alibaba:arouter-compiler:1.2.1" 
javaCompileOptions { 
            annotationProcessorOptions {
                arguments = [AROUTER_MODULE_NAME: project.getName()]
            }
        }
        
```
对于
```
annotationProcessor 'com.alibaba:arouter-compiler:1.1.4'
javaCompileOptions {
            annotationProcessorOptions {
                arguments = [moduleName: project.getName()]
            }
        }
```
