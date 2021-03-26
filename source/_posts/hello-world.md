---
title: Hello World
---
Test

<!--more-->

```c++
#include<opencv2/opencv.hpp>
#include<opencv2/highgui.hpp>
using namespace cv;

int main()
{
    Mat img=imread("avator.jpg");
    cv::imshow("image",img);
    cv::waitKey();
    return 0;
}

```

