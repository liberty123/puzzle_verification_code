# puzzle_verification_code
关于拼图验证码的解决思路

拼图拖动的验证码，需要解决的两个问题：
1:拖动的距离。  

  （1）：通过调试工具可以看到拼图的验证码是分为两张图片，一张大图，一张小图，将两张图片下载下来。  
  
  （2）：然后做一些处理，通过对比，算出距离，（这个距离有的可以直接使用，有的是不可以的，例如QQ登录的时候 下载的图片尺寸是比界面上显示的要大的，所以针对各平台，要进行缩放）。


2:拖动的时候的抖动
