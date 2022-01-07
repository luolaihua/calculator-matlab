# calculator-matlab
a calculator devoloped with matlab

一款使用matlab编写的语音计算器，界面如下图，可以设置语音模式和静音模式：

![image-20220107143538339](README.assets/202201071437801.png)

![image-20220107143603880](README.assets/202201071436944.png)

- calculator.m中为计算器软件实现代码
- calculator.fig为界面设计文件

语音文件为wav格式，用于按键时的发音：

![image-20220107150001503](README.assets/image-20220107150001503.png)

此外，在wav文件夹中另存了三种wav计算器语音文件，用于替换不同声音的语音播报。

![image-20220107150133341](README.assets/image-20220107150133341.png)



```matlab
% CACULATOR MATLAB code for caculator.fig
%      CACULATOR, by itself, creates a new CACULATOR or raises the existing
%      singleton*.
%
%      H = CACULATOR returns the handle to a new CACULATOR or the handle to
%      the existing singleton*.
%
%      CACULATOR('CALLBACK',hObject,eventData,handles,...) calls the local
%      function named CALLBACK in CACULATOR.M with the given input arguments.
%
%      CACULATOR('Property','Value',...) creates a new CACULATOR or raises the
%      existing singleton*.  Starting from the left, property value pairs are
%      applied to the GUI before caculator_OpeningFcn gets called.  An
%      unrecognized property name or invalid value makes property application
%      stop.  All inputs are passed to caculator_OpeningFcn via varargin.
%
%      *See GUI Options on GUIDE's Tools menu.  Choose "GUI allows only one
%      instance to run (singleton)".
%
% See also: GUIDE, GUIDATA, GUIHANDLES

% Edit the above text to modify the response to help caculator

% Last Modified by GUIDE v2.5 05-Jun-2018 19:21:32
```

