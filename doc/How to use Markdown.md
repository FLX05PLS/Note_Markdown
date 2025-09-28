# 一级标题，#

## 二级标题，##

#### 最高四级标题，####
>嵌套功能 >
>>引用 >>
>>>>>>>可以叠 >>>>>>>

1.  带数字的列表
   - -能用，不带数字的列表
   + +能用
   * *能用
  
2. 列表2
   1. 能带数字
   2. 能带数字
   
3. 代办
   - [ ] 打一个[ ]，后面带空格
   - [ ] [ ]中间需要带空格
   - [x] [ ]中间填x  

4. 表格，底下空一行

|写表头|和对齐方式|和表格内容|
|:--|:--:|--:|
|:-|:-:|-:|
|左对齐|中间对齐|右对齐|

5. 分割线打***
   ***  

6. 字体
   - *斜体* * *
   - ==高亮== == ==
   - **粗体** ** **
   - ***斜粗体*** *** ***
   - ~~删除~~ ~~ ~~
   - <u>下划线</u> ```<u> </u>```

7. 脚注[^1] 需要打```[^1]:```解释  
  [^1]: 需要解释    
    
8. 代码  

`hello`

```  
#include<stdio.h>

#include"flx.h"

int main()
{

    printf("hello world\n");
    printf("the num \t of flx: %d", FLX);
    getchar();  // 等待用户按下回车才退出
    printf("the num \t of flx: %d", FLX);
    getchar();  // 等待用户按下回车才退出
    printf("the num \t of flx: %d", FLX);
    getchar();  // 等待用户按下回车才退出
    // return 0;
}
```
9.  链接直接贴https://github.com/
    - 或者[点击这个链接][后面随便写点什么，记得解释]，下面需要空行
  
 [后面随便写点什么，记得解释]:https://github.com/  

10.  图片

<div align="center">
   <img src="../img/picture-example.jpg" alt="Building-Selected" width="55%" />
</div>
