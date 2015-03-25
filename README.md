《OpenCV3编程入门》书本配套源代码
==============================
####《Introduction to OpenCV3 Programming》Book Source Code<br>

![](http://img.blog.csdn.net/20150325155409850)  
<br>本书有OpenCV2、OpenCV3两套独立的书本配套示例程序供选择使用。
<br>  有4个部分11章，共有95个主线示例程序，为方便大家查阅和学习，总结成如下。
#正文部分源代码
##第一部分 快速上手OpenCV
		1	OpenCV环境配置的测试用例	1.3.8
		2	快速上手OpenCV的第一个程序：图像显示	1.4.1
		3	快速上手OpenCV的第二个程序：图像腐蚀	1.4.2
		4	快速上手OpenCV的第三个程序：blur图像模糊	1.4.3
		5	快速上手OpenCV的第四个程序：canny边缘检测	1.4.4
		6	读取并播放视频	1.5.1
		7	调用摄像头采集图像	1.5.2
		8	官方例程引导、赏析之彩色目标跟踪：Camshift	2.1.1
		9	官方例程引导、赏析之光流：optical flow	2.1.2
		10	官方例程引导、赏析之点追踪：lkdemo	2.1.3
		11	官方例程引导、赏析之人脸识别：objectDetection	2.1.4
		12	官方例程引导、赏析之支持向量机：支持向量机引导	2.1.5
		13	官方例程引导、赏析之支持向量机：处理线性不可分数据	2.1.5
		14	printf函数的用法示例	2.6.2
		15	用imwrite函数生成png透明图	3.1.8
		16	综合示例程序：图像的载入、显示与输出	3.1.9
		17	为程序界面添加滑动条	3.2.1
		18	鼠标操作示例	3.3
##第二部分 初探core组件	
		19	基础图像容器Mat类的使用	4.1.7
		20	用OpenCV进行基本绘图	4.3
		21	操作图像中像素的方法一：用指针访问像素	5.1.5、5.1.6
		22	操作图像中像素的方法二：用迭代器操作像素	5.1.5、5.1.6
		23	操作图像中像素的方法三：动态地址计算	5.1.5、5.1.6
		24	遍历图像中像素的14种方法	5.1.6
		25	初级图像混合	5.2.4
		26	多通道图像混合	5.3.3
		27	图像对比度、亮度值调整	5.4.3
		28	离散傅里叶变换	5.5.8
		29	XML和YAML文件的写入	5.6.3
		30	XML和YAML文件的读取	5.6.4、
##第三部分 掌握imgproc组件	
		31	方框滤波：boxFilter函数的使用	6.1.11
		32	均值滤波：blur函数的使用	6.1.11
		33	高斯滤波：GaussianBlur函数的使用	6.1.11
		34	综合示例：图像线性滤波	6.1.12
		35	中值滤波：medianBlur函数的使用	6.2.4
		36	双边滤波：bilateralFilter函数的使用	6.2.4
		37	综合示例：图像滤波	6.2.5
		38	膨胀：dilate函数的使用	6.3.5
		39	腐蚀：erode函数的使用	6.3.5
		40	综合示例：腐蚀与膨胀	6.3.6
		41	用morphologyEx()函数实现形态学膨胀	6.4.8
		42	用morphologyEx()函数实现形态学腐蚀	6.4.8
		43	用morphologyEx()函数实现形态学开运算	6.4.8
		44	用morphologyEx()函数实现形态学闭运算	6.4.8
		45	用morphologyEx()函数实现形态学梯度	6.4.8
		46	用morphologyEx()函数实现形态学“顶帽”	6.4.8
		47	用morphologyEx()函数实现形态学“黑帽”	6.4.8
		48	综合示例：形态学滤波	6.4.9
		49	漫水填充算法：floodFill函数	6.5.3
		50	综合示例：漫水填充	6.5.4
		51	尺寸调整：resize()函数的使用	6.6.5
		52	向上采样图像金字塔：pyrUp()函数的使用	6.6.6
		53	向下采样图像金字塔：pyrDown()函数的使用	6.6.6
		54	综合示例：图像金字塔与图片尺寸缩放	6.6.7
		55	示例程序：基本阈值操作	6.7.3
		56	Canny边缘检测	7.1.2
		57	Sobel 算子的使用	7.1.3
		58	Laplacian算子的使用	7.1.4
		59	Scharr滤波器	7.1.5
		60	综合示例：边缘检测	7.1.6
		61	标准霍夫变换：HoughLines()函数的使用	7.2.4
		62	累计概率霍夫变换：HoughLinesP()函数	7.2.5
		63	霍夫圆变换：HoughCircles()函数	7.2.8
		64	综合示例：霍夫变换	7.2.9
		65	实现重映射：remap()函数	7.3.3
		66	综合示例程序：实现多种重映射	7.3.4
		67	仿射变换	7.4.5
		68	直方图均衡化	7.5.3
		69	轮廓查找	8.1.3
		70	查找并绘制轮廓	8.1.4
		71	凸包检测基础	8.2.3
		72	寻找和绘制物体的凸包	8.2.4
		73	创建包围轮廓的矩形边界	8.3.6
		74	创建包围轮廓的圆形边界	8.3.7
		75	使用多边形包围轮廓	8.3.8
		76	图像轮廓矩	8.4.4
		77	分水岭算法的使用	8.5.2
		78	实现图像修补	8.6.2
		79	H-S二维直方图的绘制	9.2.3
		80	一维直方图的绘制	9.2.4
		81	RGB三色直方图的绘制	9.2.5
		82	直方图对比	9.3.2
		83	反向投影	9.4.7
		84	模板匹配	9.5.3
		
##第四部分 深入featrue2d组件	
		85	实现Harris角点检测：cornerHarris()函数的使用	10.1.4
		86	harris角点检测与绘制	10.1.5
		87	Shi-Tomasi角点检测	10.2.3
		88	亚像素级角点检测	10.3.3
		89	SURF特征点检测	11.1.6
		90	SURF特征提取	11.2.3
		91	使用FLANN进行特征点匹配	11.3.3
		92	FLANN结合SURF进行关键点的描述和匹配	11.3.4
		93	SIFT配合暴力匹配进行关键点描述和提取	11.3.5
		94	寻找已知物体	11.4.3
		95	利用ORB算法进行关键点的描述与匹配	11.5.4



#附赠的进阶程序一览

本书额外附赠了OpenCV2版的21个相较于正文主线的示例代码稍微复杂一些的程序源代码。
现将附赠的21个示例程序列举如下：

		1	随机图形和文字生成示例（randomtext）
		2	生成彩色色条（gencolors）	
		3	卡尔曼滤波（kalman）	
		4	渐变过渡各种图形滤波（median_blur）
		5	距离变换（distanceTransform）
		6	把图像映射到极指数空间（Log Polar）
		7	filter2D滤波器的用法	
		8	grabCut图像分割示例	
		9	MeanShift图像分割示例
		10	用滑动控制图像直方图
		11	找到图像最小的封闭轮廓
		12	Retina特征点检测
		13	摄像头帧数检测
		14	视频截图
		15	对视频的快速角点检测
		16	视频简单色彩检测
		17	跟踪分割视频中运动的物体
		18	视频的直方图反向投影。
		19	计算视频中两个图像区域的相似度
		20	视频前后背景分离
		21	用高斯背景建模分离背景


<br>
[【书本勘误&维护博文】](http://blog.csdn.net/poem_qianmo/article/details/44416709)

![](http://img.blog.csdn.net/20150325202951885)  
<br>Enjoy~

