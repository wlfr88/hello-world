# hello-world
Just another repository
#include<opencv2/opencv.hpp>
using namespace cv;
int main()
{
	Mat a = imread("1.jpg",1);
	imshow("a",a);
	cvWaitKey(0);
	return 0;
}
