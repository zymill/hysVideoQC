# hysVideoQC

video quality comparator base on libvmaf and ffmpeg
 (video quality comparator 视频质量比较工具) 

## video Help guide

[Video Help Guide](https://www.zhihu.com/zvideo/1547348112431271936)

## Features

1.Reference file (源视频文件)
```
* Support MP4/MPEGTS/MKV/AVI/FLV/3GP/MOV/VOB/MXF/MPG/M2TS
* Support ES files: h264/h265(suffix with.264 .265 .266 .h264 .h265 .h266) (266/h266 in future)
* Support ES files: m2v/m4v/mpeg(suffix with .m2v .m4v .mpeg)
* Support ES files: AVS/AVS2/AVS3(suffix with .avs .avs2 .avs3)  (avs3 in future) 
* Support ES files: VP8/VP9/AV1(suffix with .vp8 .vp9 .av1)
* Support Raw YUV(suffix with .yuv .raw .y4m) Files
```

2. Distortion files (转码后的文件)
```
* Support file format same as reference file
* Maximum support 8 files in one QC task
* Support file details based on FFMPEG
```
3. VMAF options
```
* Support PSNR/SSIM/MS_SSIM/VMAF
* Support JSON/XML/CSV files based on VMAF 
* Support compare part of file if necessary.
```
4. Basic options
```
* Support YUV parameters setting for Raw file
* Support open, delete, reset reference/distortion file(s)
* Support start/stop compare task.
```

## Note

Software files be splitted to two 7z files because the single file size is uplimited <= 25MB.

Please download both "hysVideoQC v0.0.2.004.7z" and "hysVideoQc v0.0.2.001_ffmpeg_dll.7z", copy all ffmpeg dll files to unziped directory hysVideoQC v0.0.2.004 before you start hysVideoQC.

Of course, you can download the whole 7z file from below Chinese Baidu web url. (Baidu's Pan)

[Baidu Pan](https://pan.baidu.com/s/18esWF4m30fDlriKtE126KA) 

**提取码(pin)：vmaf**

Please email to me, if you have good idea or meet any question.

Thanks!


## 图示1
![mainui](https://user-images.githubusercontent.com/18504455/233099874-25f17238-fb97-433a-b023-f7d077008842.png)

## 图示2
![mainui1](https://user-images.githubusercontent.com/18504455/233099939-d2084e2e-9796-47a9-a73a-82915d517739.png)

## 图示3
![mainui2](https://user-images.githubusercontent.com/18504455/233100052-ad1e1bee-75a3-497b-924d-b4f7eda7d01a.png)

## 图示4
![mainui3](https://user-images.githubusercontent.com/18504455/233100161-54bed100-b70b-4b5f-b1e8-d442bf3cd4b8.png)

## 图示5
![mainui4](https://user-images.githubusercontent.com/18504455/233100280-ebc0cdbf-dce5-4d29-b886-15b53ece1a9f.png)


hysVideoQC 下载地址：

	* 百度网盘  https://pan.baidu.com/s/18esWF4m30fDlriKtE126KA  提取码(pin)：vmaf
	
	* Github    https://github.com/zymill/hysVideoQC


## Author

	* Email  : hybase@qq.com

