# hysVideoQC
video quality comparator base on libvmaf and ffmpeg

# 概述

hysVideoQC (video quality comparator 视频质量比较工具) 

本软件是因作者平常自身工作需要，基于开源项目VMAF和FFMPEG开发的一款 QT 图形界面工具。它可用于对比转码前后的失真变化，跟踪不同参数对视频转码的影响。
因为工具的使用者不多，可能存在一些未知的问题。希望使用的朋友多多包涵，如果使用过程中有好的建议或遇到问题，请联系作者（联系方式请参考文章尾部），先致谢！

hysVideoQC 下载地址：
	* 百度网盘  https://pan.baidu.com/s/18esWF4m30fDlriKtE126KA  提取码：vmaf
	* Github    https://github.com/zymill/hysVideoQC

## 功能特征

1.Reference file (源视频文件)
	* Support MP4/MPEGTS/MKV/AVI/FLV/3GP/MOV/VOB/MXF/MPG/M2TS
	* Support ES files: h264/h265(suffix with.264 .265 .266 .h264 .h265 .h266) (266/h266 in future)
	* Support ES files: m2v/m4v/mpge(suffix with .m2v .m4v .mpeg)
	* Support ES files: AVS/AVS2/AVS3(suffix with .avs .avs2 .avs3)  (avs3 in future) 
	* Support ES files: VP8/VP9/AV1(suffix with .vp8 .vp9 .av1)
	* Support Raw YUV(suffix with .yuv .raw .y4m) Files

2. Distortion files (转码后的文件)
	* Support file format same as reference file
	* Maximum support 8 files in one QC task
	* Support file details based on FFMPEG

3. VMAF options
	* Support PSNR/SSIM/MS_SSIM/VMAF
	* Support JSON/XML/CSV files based on VMAF 
	* Support compare part of file if necessary.

4. Basic options
	* Support YUV parameters setting for Raw file
	* Support open, delete, reset reference/distortion file(s)
	* Support start/stop compare task.
