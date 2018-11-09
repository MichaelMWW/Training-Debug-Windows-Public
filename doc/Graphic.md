## 准备工作、工具、环境和Demo
- 环境：
	- OS：Win7 / Win8.1 / Win10
	- IDE：VS2015 / VS2017
- 下载：[工具 & Demo](https://share.weiyun.com/5SHAbCW)
- 源码：[Github](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/tree/master/src)，[下载](https://github.com/wu-wenxiang/Training-Debug-Windows-Public/archive/master.zip)

## 内容
- Native C++ Desktop Rendering Introduction & Best Practice
	- Rendering Pipeline
	- ![渲染管线.jpg](https://pic4.zhimg.com/v2-1e286dd517c717e3f1c48792275f7e87_r.jpg)
	- Rasterization
	- ![三角形的软件光栅化.png](http://hi.csdn.net/attachment/201103/8/8458191_1299585635RfNA.png)
	- [Overview of the Windows Graphics Architecture](https://docs.microsoft.com/en-us/windows/desktop/learnwin32/overview-of-the-windows-graphics-architecture)
		- [GDI](https://msdn.microsoft.com/en-us/library/ms969913.aspx)
		- [GDI+](https://docs.microsoft.com/en-us/windows/desktop/gdiplus/-gdiplus-gdi-start)
		- [OpenGL](https://learnopengl.com/Getting-started/OpenGL)
		- [Unity](https://link.zhihu.com/?target=http%3A//unity3d.com/learn/tutorials/modules) 
	- [Comparing Direct2D and GDI Hardware Acceleration](https://docs.microsoft.com/en-us/windows/desktop/direct2d/comparing-direct2d-and-gdi)
	- [Direct2D in action](https://docs.microsoft.com/en-us/windows/desktop/learnwin32/your-first-direct2d-program)
	- Howto: [Improving the performance of Direct2D apps](https://docs.microsoft.com/en-us/windows/desktop/direct2d/improving-direct2d-performance)
- Performance Tunning
	- [Debugging Tips for the Windows Display Driver Model](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/debugging-tips-for-the-windows-vista-display-driver-model)
	- Tools: [Sysinternals](https://docs.microsoft.com/en-us/sysinternals) (Procmon / ProcExp / Handle, etc)
	- [Profiling native C++ rendering apps](https://docs.microsoft.com/en-us/windows/desktop/direct2d/profiling-directx-applications)
		- [Xperf](https://blogs.msdn.microsoft.com/ntdebugging/2008/04/03/windows-performance-toolkit-xperf/) 
		- [GPUView](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/using-gpuview)
		- [UIforETW](https://github.com/google/UIforETW/releases)