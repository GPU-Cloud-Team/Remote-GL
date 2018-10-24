## Introduction
![](https://raw.githubusercontent.com/GPU-Cloud-Team/Remote-GL/gh-pages/remote-gl.png)

Remote-GL is a client-server system that uses a remote GPU to implement native OpenGL functionality. 
The key point of Remote-GL is that: The client passes all opengl instrutions to the server side and recieve the result from the server.

**The client side**: 
 1. Listen OpenGL API calls.
 2. Send the calls to the server.
 3. Receive the result.
 4. Display the result.	


**The server side**:
 1. Receive the instructions and data transported from the client side.
 2. Allocate necessary memory space and kernels of GPUs and the execute the instructions.
 3. Send back the result.


**The Network layer**:
 1. Control Channel: transport control instructions and metadata.
 2. Data Channel: transport OpenGL API calls and related data. 



## Publications
[Comming soon]


## Code
Source code: [Here](https://github.com/GPU-Cloud-Team/Remote-GL)


## Demo
Here is the demo of multi-clients with single server:


![](https://raw.githubusercontent.com/GPU-Cloud-Team/Remote-GL/gh-pages/demo.png)


Here is the video demo of Remote-GL:


![](https://raw.githubusercontent.com/GPU-Cloud-Team/Remote-GL/gh-pages/demo-gif.gif)



## About US

[Trusted Cloud Group](http://tcloud.sjtu.edu.cn/), Shanghai Jiaotong University

[Zhengwei Qi](http://tcloud.sjtu.edu.cn/people/zhengwei/) :  qizhwei AT sjtu.edu.cn <br/>
[Dongji Tang]() :  dongjitang AT outlook.com <br/>
[Yun Wang]()    :  yunwang94 AT sjtu.edu.cn <br/>
[Linsheng Li]() :  lilinsheng1 AT sjtu.edu.cn <br/>

 
