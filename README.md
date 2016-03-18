# Convert NV12 & NV21 to YUV420P

Simple and easy-understand C++ codes for converting NV12 & NV21 to YUV420P

## Basic understanding of these format

These three format all have NxM Y plane followed by (N/2)x(M/2) V and U planes.

For example N = 6 & M = 4
the YUV420P 
![image](http://p.blog.csdn.net/images/p_blog_csdn_net/hhygcy/EntryImages/20081125/yv12.png)

the NV12
![image](http://p.blog.csdn.net/images/p_blog_csdn_net/hhygcy/EntryImages/20081125/nv12.png)

and the difference between NV12 and NV21 is that the position of U and V is opposite

## References

* http://blog.csdn.net/fanbird2008/article/details/8232673
* http://www.fourcc.org/yuv.php