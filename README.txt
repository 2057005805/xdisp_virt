
���ǻ���windowsƽ̨��Զ��������Ƴ������°汾���汾������
�ṩԶ�̿��ƣ�֧������ͷ����·��Ƶ��������
�Լ�����Զ������˳���Ĺۿ���Ƶ������Ϸ�ȶ�ý�����ֹ��ܡ�

�����ƶ�֧�ֵ�ƽ̨���� windowsϵ�У��� XP��WIN7�� WIN8�� WIN10����
���ƶ�֧��ԭ���ͻ��ˣ�Ҳ֧����ҳ�ͻ��ˡ�
��ҳ�ͻ���֧�ֵ����������Chrome��FireFox��Apple Safari��Microsoft Edge��Opera�Ⱦ߱��ִ����ܵ��������
��֧��IE�Լ�IE�ں����������ҳ�ͻ��˲���ƽ̨���������в���ϵͳƽ̨��֧�֣������ƶ�ƽ̨��PCƽ̨����
���紫���֧�ֲ����ܵ����Ĵ��䣻Ҳ֧��SSL���ܴ��䣬Ϊ���ݴ��������ȫ��֤��

��������ӵ�ĳ���̶���������Ҳ���ṩ�Զ����¹��ܡ���������������˷��ʼ�
fanxiushu@163.com
���߷������BLOG:
CSDN: https://blog.csdn.net/fanxiushu
GITHUB: https://github.com/fanxiushu

binĿ¼��������ִ���ļ�

driverĿ¼�Ǿ���������û��ǩ����

hid_driverĿ¼�������HID������������û��ǩ����

htmlĿ¼����������ҳ�Լ�javascript�ű���htmlĿ¼�Ѿ�������� xdisp_virt.exe����

imageĿ¼�ǳ������е�һЩЧ��ͼ��

2019-5�¸��£�
    1���������˶� ������ xdisp_virt.exe��xdisp_virt.ini �����ļ�������ͨ����ҳ��ʽ�������ã�����������ǰһ���ǵô�xdisp_virt.ini�ļ��������á�
    2���� DirectX HOOK ��̬������ xdisp_virt.exe �����У������� ����DXHOOK������£����Զ��ӳ����ͷų� dx_hook32.dll��dx_hook64.dll��̬�⡣
    3,  ��һ���Ż��ɼ�ʱ������ʹ��NtSetTimerResolution ��ϵͳʱ�侫��������󣬴Ӷ�ȷ��Sleep��ȷ˯�ߣ�
     ��֤ͼ��ɼ����������ȷ������������ 60 FPS�����ĸ߲ɼ��ʡ�
     ������ҳ�ͻ��˱������Դ����ͦ�󣬿����޷����ܸ߲ɼ��ʣ���ʹ���������õ���ҳ�ͻ��˻���ʹ��ԭ���ͻ��ˡ�

2019-04 �������ܣ�
     1��  ֧�ֶ���ʾ��Զ�̿��ƣ����԰Ѷ����ʾ�ϲ���һ����ߵ�����ʾ��
     2��  ��WIN7��WIN10��ƽ̨������ DirectX HOOK ��ʽ��ȡȫ����ռ����, ��ҪĿ����Ϊ������Զ�̿�������ĳЩ���͵�3Dȫ����ռ��Ϸ��
     3��  ��������HID����������������Ӧ�ò��������ģ����ƣ���ҪĿ����Ϊ�˽��ĳЩ��Ϸ�޷���Ӧ�ò�ģ�������̿��ơ�


Bug fixed:
    1, ������ҳ�ͻ���������chrome��firefox�У�Զ����ʾ���ڲ��ܸ�������������Զ��������⣬
	   ������� xdisp_h264.js�ű�����changeCanvasSize�ж�ȫ���жϡ�2019-01-25

���򿪷�������Դ����˵����
	xdisp_virt��xdisp_server������ʹ��C/C++���ԣ�VS2015�������ɣ�����ʹ�õ��Ŀ�Դ����Ǿ�̬���������
	CSDN�Ϸ����˵�һ�汾��ץ�����ִ��룬GITHUB������xdisp_virt�������ӹ��ܴ���push_stream
	������������RTSP,RTMP���������߱���Ϊ����MP4,MKV��Ƶ�ļ���,
	�����htmlĿ¼��������ҳ�ͻ��˵�ȫ��Դ���롣
	����֮�⣬����Դ���벢����Դ���Դ˴������㾴���½⡣
   

��ز��ͣ�
https://blog.csdn.net/fanxiushu/article/details/81905680
https://blog.csdn.net/fanxiushu/article/details/78869719

=====================================================================
This is the latest version of the remote desktop control program based on the windows platform (version two).
Provide remote control, support camera, multi-channel audio and push flow.
And can watch videos, play games and other multimedia entertainment functions on the remote desktop��

The platform supported by the control end includes windows series (from XP, WIN7, WIN8, WIN10).
The control side supports native clients, and also supports web clients.
Web client-supported browsers include Chrome, FireFox, Apple Safari, Microsoft Edge, Opera and other modern browsers.
IE and IE kernel browser are not supported. Web client is open platform, almost all operating system platforms support (including mobile platforms and PC platforms).
Network transmission not only supports unencrypted plaintext transmission, but also supports SSL encrypted transmission, providing security for data transmission.

The software does not link to a fixed server, nor does it provide automatic update. If there is any need, please send me an email.
Fanxiushu@163.com
Or visit related BLOG:
CSDN: https://blog.csdn.net/fanxiushu
GITHUB: https://github.com/fanxiushu

The bin directory contains the xdisp_virt.exe program, and xdisp_virt.ini is its configuration file.
The xdisp_server.exe program, xdisp_server.ini is its configuration file.
The configuration file has a detailed description of each field.
It has been configured as a default setting to run the EXE program directly.
xdisp_server.exe provides server transit to solve intranet access problems and to bring together multiple controlled machines.
There are certain benefits for maintainers.

The driver directory is mirrored and has no signature.
The HTML directory contains all the web pages and JavaScript scripts, 
and the HTML directory has been packed into the xdisp_virt.exe program.
The image directory is some effect diagram of the program running.

for detail:
https://blog.csdn.net/fanxiushu/article/details/81905680
https://blog.csdn.net/fanxiushu/article/details/78869719

fanxiushu 2017-2018


