# XYPieChart
一个非常好用的饼状图控件
## 效果图
![](https://github.com/lover0920/XYPieChart/raw/master/饼状图.png)
## 使用
```
    _pieChart = [[XYPieChart alloc]initWithFrame:CGRectMake(12, 0, SCREEN_WIDTH-24, SCREEN_WIDTH-24)];
    _pieChart.dataSource = self;
    _pieChart.delegate = self;
    _pieChart.startPieAngle = M_PI/2 + M_PI;//起始点
    _pieChart.animationSpeed = 1.0;//动画时长
    _pieChart.pieRadius = (SCREEN_WIDTH-120)/2;//半径
    _pieChart.showPercentage = NO;
    _pieChart.showLabel = YES;
    _pieChart.labelColor = UIColorTitle2;
    _pieChart.labelFont = [UIFont systemFontOfSize:14];
    _pieChart.labelRadius = (SCREEN_WIDTH-80)/2;
    [_pieChart setPieBackgroundColor:UIColorWhite];
```
