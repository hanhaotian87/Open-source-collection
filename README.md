# Open-source-collection
优秀开源项目收集
## Android开源项目
### Android 架构
1. 简易的MVP架构[https://github.com/antoniolg/androidmvp](https://github.com/antoniolg/androidmvp)
2. MVVM实例--MVVM_Hacker_News[https://github.com/hitherejoe/MVVM_Hacker_News](https://github.com/hitherejoe/MVVM_Hacker_News)
![MVVM_Hacker_News示例图](https://github.com/hitherejoe/MVVM_Hacker_News/blob/master/images/screens.png)

### Android 应用搭建快捷组件
1. **retrofit** Type-safe HTTP client for Android and Java by Square, Inc. Android最好的HTTP框架   
      项目地址：[https://github.com/square/retrofit](https://github.com/square/retrofit)    
      项目文档：[http://square.github.io/retrofit/](http://square.github.io/retrofit/)    
2. **picasso** A powerful image downloading and caching library for Android. square又一款杰作，图片加载组建    
      项目地址：[https://github.com/square/picasso](https://github.com/square/picasso)    
      项目文档：[http://square.github.io/picasso/](http://square.github.io/picasso/)    
      ![示例图](https://github.com/square/picasso/blob/master/website/static/sample.png)    
3. **glide** An image loading and caching library for Android focused on smooth scrolling. **picasso**基础上更进一步图片加载组建    
      项目地址：[https://github.com/bumptech/glide](https://github.com/bumptech/glide)    
      ![图标](https://github.com/bumptech/glide/blob/master/static/glide_logo.png)    
4. **greenDAO** greenDAO is a light & fast ORM solution for Android that maps objects to SQLite databases.数据库组建         
      项目地址：[https://github.com/greenrobot/greenDAO](https://github.com/greenrobot/greenDAO)    
      项目文档：[http://greenrobot.org/greendao/](http://greenrobot.org/greendao/)    
greenDAO's unique set of features:
Rock solid: greenDAO has been around since 2011 and is used by countless famous apps    
Super simple: concise and straight-forward API    
Small: The library is <100K and it's just plain Java jar (no CPU dependent native parts)    
Fast: Probably the fastest ORM for Android, driven by intelligent code generation    
Safe and expressive query API: QueryBuilder uses property constants to avoid typos    
Powerful joins: query across entities and even chain joins for complex relations    
Flexible property types: use custom classes or enums to represent data in your entity    
5. **flatbuffers** Memory Efficient Serialization Library google出品高效序列化库    
    项目地址：[https://github.com/google/flatbuffers](https://github.com/google/flatbuffers)    
    项目文档：[http://google.github.io/flatbuffers/](http://google.github.io/flatbuffers/)    
    #### Supported operating systems    
   -  Android    
   -  Windows    
   -  MacOS X    
   -  Linux      
> 为什么要使用Google FlatBuffers    
对序列化数据的访问不需要打包和拆包——它将序列化数据存储在缓存中，这些数据既可以存储在文件中，又可以通过网络原样传输，而没有任何解析开销；    
内存效率和速度——访问数据时的唯一内存需求就是缓冲区，不需要额外的内存分配。 这里可查看详细的 基准测试；    
扩展性、灵活性——它支持的可选字段意味着不仅能获得很好的前向/后向兼容性（对于长生命周期的游戏来说尤其重要，因为不需要每个新版本都更新所有数据）；    
最小代码依赖——仅仅需要自动生成的少量代码和一个单一的头文件依赖，很容易集成到现有系统中。再次，看基准部分细节；    
强类型设计——尽可能使错误出现在编译期，而不是等到运行期才手动检查和修正；    
使用简单——生成的C++代码提供了简单的访问和构造接口；而且如果需要，通过一个可选功能可以用来在运行时高效解析Schema和类JSON格式的文本；   
跨平台——支持C++11、Java，而不需要任何依赖库；在最新的gcc、clang、vs2010等编译器上工作良好；    

