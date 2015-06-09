# DemoInPutPasswordView
仿微信支付密码输入框

其中的文本框使用了第三方库WTReTextField 
详见：https://github.com/pieceofsummer/WTReTextField 

使用：
1.将相关类导入到你的项目中
2.添加引用#import "LMPopInputPasswordView.h"，实现委托LMPopInputPassViewDelegate
3.创建对象并设置委托，弹出视图：
LMPopInputPasswordView *popView = [[LMPopInputPasswordView alloc]init];
popView.frame = CGRectMake((self.view.frame.size.width - 250)*0.5, 50, 250, 150);
popView.delegate = self;
[popView pop];

效果图：
/Users/tkinghr/Desktop/inputviewrecord.gif