# Frosted-glass
使用UIToolbar写一个简单的毛玻璃效果

开始不知道使用UIToolbar来写这个毛玻璃效果，走了不少弯路，也没有解决领导交给的任务。 
1、主要利用UIToolbar的barStyle属性，将其当做UIView来使用。
UIBarStyleDefault  //默认
UIBarStyleBlack    //黑
UIBarStyleBlackOpaque    //
UIBarStyleBlackTranslucent
2、作为毛玻璃效果，必须有背景。所以这个只能是盖在当前控制器的上面来实现。
