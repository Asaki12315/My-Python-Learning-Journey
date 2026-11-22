# My-Python-Learning-Journey
## 项目介绍
* 项目简介：本项目是一个用Python编写的小工具，用于解决日常数学计算的问题
* 文件说明：
  * 1.`bmi.ipynb`主要用于计算个人体脂率（bmi），有助于评估个人的身体健康水平
  * 2.`rectangle.ipynb`主要用于计算长方体的表面积，可用于估计日常生活中如礼物盒包装纸等商品的选购
* 代码说明
  * 1.`bmi.ipynb`中，`culculate_bmi`用于输入姓名、身高、体重参数，通过`bmi=weight/(height*height)`计算bmi数值，由`if`条件判读bmi所属范围并输出
  * ```python
    def culculate_bmi(person,height,weight): 
    print(person + "的身高：" + str(height) + "米 \t 体重：" + str(weight) + "千克")
    bmi=weight/(height*height)                  
    print(person + "的bmi指数为："+str(bmi))        
    if bmi<18.5:
        print("您的体重过轻")
    if bmi>=18.5 and bmi<24.9:
        print("您的体重处于正常范围")
    if bmi>=24.9 and bmi<29.9:
        print("您的体重过重")
    if bmi>=29.9:
        print("您的体重属于肥胖")
  * 2.`rectangle.ipynb`中，`surf_rectangle`用于输入长方体的长、宽、高参数，并将计算后的表面积储存在`result`中输出
  * ```python
    def surf_rectangle(a, b, c):
      result = (a*b + b*c + a*c)*2
      return result
    s = surf_rectangle(5,8,9)
    print(s)
## 学习心得与规划
  * 通过本次任务，我初步认识了Github这一平台，并学习了如何创建仓库。在未来，我能够借助这一平台获取他人分享的代码与经验，扩展自己的学习渠道，并在需要时更便捷地获取工具来源。同时，这也反向督促我精进自身的编程水平，使自己得以更快更精准地阅读与辨识他人编写的代码，发现其中的优点与漏洞。而GitHub简洁清晰的界面与条目分类，也使我可以利用它来存放自己编写的代码或一时的灵感，便于日后回顾优化。此外，我个人认为Markdown语法也是一个很值得深入学习的工具，如果不考虑中英文切换（如全英文写作），这一语法能够很好地保持写作的连贯性，降低切换成本。尤其是针对类似涉及代码的写作，能够把格式区分得很清晰。
