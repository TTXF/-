# -
利用图像分割和图像识别技术，将对图像水印信息时间和经纬度计算质检
本文代码可提取出每张照片的水印信息，转化为文字数据，然后对文字信息中的时间和经纬度数据进行计算，从而检验工单时间和经纬度信息是否合理。按次工单每个工单大约有42张左右，每三个一组，每组照片分为整改前、整改中、整改后，每张照片左下角都有水印信息，一般人工需要对水印信息里的时间和经纬度信息进行检验，每组照片整改前和整改后时间不得小于10分钟，每组照片地点间隔不得小于20米。此工具可快速对批量的工单照片水印信息进行质检，程序运行完将会输出不合格的照片和工单，审批人员可直接使用对工单进行驳回。
每组照片示意图：

![image](https://user-images.githubusercontent.com/31240413/215397564-203a73ff-6206-4f44-87a8-e93437cba5fa.png)
![image](https://user-images.githubusercontent.com/31240413/215397655-a312c949-2919-453a-8202-30bedcf47d23.png)
![image](https://user-images.githubusercontent.com/31240413/215397677-8174be7b-ef87-4b0c-89a7-7b4e54086e26.png)

水印数据分割示意图：

![image](https://user-images.githubusercontent.com/31240413/215397867-833ed669-7552-452f-8f9f-32d028188b85.png)
![image](https://user-images.githubusercontent.com/31240413/215397883-43671aeb-1c44-462d-89c2-4babb15b20f5.png)

水印信息转化为文字示意图：

![image](https://user-images.githubusercontent.com/31240413/215397900-4f9d5f8a-4a57-4677-80dc-a71c3490194e.png)
![image](https://user-images.githubusercontent.com/31240413/215397913-22510930-976b-4464-bf03-9f85118ddedc.png)

程序运行结果示意图：

![image](https://user-images.githubusercontent.com/31240413/215397930-fa53871b-6518-4a40-88b8-a270260a7dc7.png)
![image](https://user-images.githubusercontent.com/31240413/215397942-0646ae60-87d6-41ba-91d6-b44f3b48300a.png)
