# Entitas
>1. [Entitas项目](https://github.com/sschmid/Entitas-CSharp)
>2. [官方wiki](https://github.com/sschmid/Entitas-CSharp/wiki)
## 建议优先浏览的内容
>1. Entitas中的基本概念
>>- [CookBook](https://github.com/mzaks/EntitasCookBook) 
>>>**注意，该文档的中语法有部分已经过时**
>>- [CodeGenerator](https://github.com/sschmid/Entitas-CSharp/wiki/Code-Generator)
>2. Entitas的安装与配置
>>- [在Unity中集成Entitas](https://github.com/sschmid/Entitas-CSharp/wiki/Unity-Installation-Guide)
>>- [插件配置参考表](https://github.com/sschmid/Entitas-CSharp/wiki/Default-Plugin-Configuration)
>3. 如何通过Entitas与Unity进行交互
>>- [官方实例](https://github.com/sschmid/Entitas-CSharp/wiki/Unity-Tutorial---Simple-Entity-View-and-Movement)
## 值得注意的小坑
>1. Jenny代码生成器的配置
>> 代码生成器Jenny的配置绑定的对象是整个Unity，因此请确保：
>>>**当前工程目录下有Jenny的配置文件，并且Unity中Jenny插件与该配置文件绑定**
>>><br/> 
>>>```如果配置Jenny的过程中，显示缺少配置文件无法启动，需在它提示的目录下创建配置文件，正常启动Jenny后再对配置文件目录进行修改```
>2. Jenny使用过程中的问题
>> 1. 如何使用Jenny
>>> 1. 第一步：完成Jenny的配置，在空项目下运行Jenny，生成对应的annation，如\[Game\],\[Input\]
>>> 2. 第二步：完成所有Component的编码，运行Jenny，使Component注册到不同的annation下
>>> 3. 第三步：完成所有System的编码，运行Jenny，完成最后的代码生成
## Entitas其他资料
>1. [官方视频](https://www.youtube.com/channel/UC2q7q7tcrwWHu5GSGyt_JEQ)
>2. [官方实例](https://github.com/sschmid/Entitas-CSharp/wiki/Example-projects)
>3. [C#指南](https://docs.microsoft.com/zh-cn/dotnet/csharp/)
