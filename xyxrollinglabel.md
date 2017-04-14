#XYXRollingLabel
#使用说明
   此demo集成了跑马灯开始，暂停，反方向运动，减速运动，点击获取值的功能，很实用，无污染

####1.Property
    -(void)beginTimer;    start rolling. 
  	-(void)pauseTimer;    pause rolling. 
  	-(void)stopTimer;     stop  rolling.   
  	
####2.ClickEventBlock:<p/>
  	label.labelClickBlock = ^(NSInteger index){	
		//Your Code.
  	}; 
  	
  	