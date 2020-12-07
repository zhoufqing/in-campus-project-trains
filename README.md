# in-campus-project-trains

## 针对大三上学期项目实训总结

参考：https://blog.csdn.net/weixin_43380510/article/details/88544830?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522160491306219724842930164%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=160491306219724842930164&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~rank_v28-5-88544830.pc_first_rank_v2_rank_v28&utm_term=%E5%9B%BE%E7%89%87%E7%AF%A1%E6%94%B9%E6%A3%80%E6%B5%8B%E4%BB%A3%E7%A0%81&spm=1018.2118.3001.4449

代码来源：https://github.com/LarryJiang134/Image_manipulation_detection by LarryJiang134

源代码针对篡改过的图片进行位置检测
在源代码的基础上，修改了部分代码：
   1.修改了篡改图片的类型，copy_moce,splicing。由二分类到三分类
   2.修改了所用网络（vgg16—>resnet50）源代码中已经有了resnet的代码，但是需要加一些修改
   3.展示图片时把copy_move 和 splicing 都放在了一起 
