# Open-source-collection
优秀开源项目收集
## Android开源项目
### Android 架构
1. 简易的MVP架构 [https://github.com/antoniolg/androidmvp](https://github.com/antoniolg/androidmvp)

2. MVVM实例--MVVM_Hacker_News [https://github.com/hitherejoe/MVVM_Hacker_News](https://github.com/hitherejoe/MVVM_Hacker_News)
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

> *Supported operating systems*    
   -  Android    
   -  Windows    
   -  MacOS X    
   -  Linux  
> *为什么要使用Google FlatBuffers*   
   - 对序列化数据的访问不需要打包和拆包——它将序列化数据存储在缓存中，这些数据既可以存储在文件中，又可以通过网络原样传输，而没有任何解析开销；    
   - 内存效率和速度——访问数据时的唯一内存需求就是缓冲区，不需要额外的内存分配。 这里可查看详细的 基准测试；    
   - 扩展性、灵活性——它支持的可选字段意味着不仅能获得很好的前向/后向兼容性（对于长生命周期的游戏来说尤其重要，因为不需要每个新版本都更新 - 所有数据）；    
   - 最小代码依赖——仅仅需要自动生成的少量代码和一个单一的头文件依赖，很容易集成到现有系统中。再次，看基准部分细节；    
   - 强类型设计——尽可能使错误出现在编译期，而不是等到运行期才手动检查和修正；    
   - 使用简单——生成的C++代码提供了简单的访问和构造接口；而且如果需要，通过一个可选功能可以用来在运行时高效解析Schema和类JSON格式的文本；   
   - 跨平台——支持C++11、Java，而不需要任何依赖库；在最新的gcc、clang、vs2010等编译器上工作良好；    

6. **EventBus** Android optimized event bus that simplifies communication between Activities, Fragments, Threads, Services, etc. Less code, better quality. 优秀的事件分发组建
   项目地址： [https://github.com/greenrobot/EventBus](https://github.com/greenrobot/EventBus)    
   项目文档： [http://greenrobot.org/eventbus/](http://greenrobot.org/eventbus/)    
   EventBus is a publish/subscribe event bus optimized for Android.    
   ![示意图](https://github.com/greenrobot/EventBus/blob/master/EventBus-Publish-Subscribe.png)     

### Android 优质开源控件    
1. **AndroidRubberIndicator** A rubber indicator for ViewPager  ViewPager切换转场标记  
  项目地址：[https://github.com/LyndonChin/AndroidRubberIndicator](https://github.com/LyndonChin/AndroidRubberIndicator)    
  ![示例图](https://camo.githubusercontent.com/2ea6152b06aa5f9ca21ab7ff0a83830f73f48fbe/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3330333233342f73637265656e73686f74732f323039303830332f70616765696e64696361746f722e676966)    
2. **Android-StepsView** 一个用于记录事件步骤View 控件    
  项目地址：[https://github.com/anton46/Android-StepsView](https://github.com/anton46/Android-StepsView)    
  ![示例图](https://github.com/anton46/Android-StepsView/blob/master/image2.png)    

3. **HoloGraphLibrary** Fork of the HoloGraphLibrary by Daniel Nadeau with additionnal features  Android简化画线，bar为View    
  项目地址：[https://github.com/Androguide/HoloGraphLibrary](https://github.com/Androguide/HoloGraphLibrary)    
  ![示例图](https://camo.githubusercontent.com/3b9ab5f3c255e3796fdd3b5942679cbafe10e866/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f2d5072356e7a586e67785a6f2f5553305f524b48394447492f41414141414141415331732f616e346353334e723471592f733834342f31332b2d2b31)   
  ![示例图](https://camo.githubusercontent.com/f08be3abc22a0068c72f40ab331c7d63830a3538/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f2d397679394276636c7832342f5553305f52495a706c37492f414141414141414153326f2f6b335470623273496f46772f733834342f31332b2d2b33)  
  ![示例图](https://camo.githubusercontent.com/39c6c8de9847d2ec78d757c0e5ffcac482af8ee3/68747470733a2f2f6c68362e676f6f676c6575736572636f6e74656e742e636f6d2f2d4164306c4c64794b3163412f5553305f52425963714b492f41414141414141415332302f6c51387a4c6f5f565369512f733834342f31332b2d2b35)  

4. **AVLoadingIndicatorView** Nice loading animations for Android 一个loading 集合    
   项目地址：[https://github.com/81813780/AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)    
   ![示例图](https://github.com/81813780/AVLoadingIndicatorView/blob/master/Demo2.gif)   

5. **Material-Animations** Android Transition animations explanation with examples.     
   项目地址：[https://github.com/lgvalle/Material-Animations](https://github.com/lgvalle/Material-Animations)    
   ![示例图](https://raw.githubusercontent.com/lgvalle/Material-Animations/master/screenshots/transition_explode.gif) ![示例图](https://raw.githubusercontent.com/lgvalle/Material-Animations/master/screenshots/transition_slide.gif) ![示例图](https://raw.githubusercontent.com/lgvalle/Material-Animations/master/screenshots/transition_fade.gif)   

6. **NumberCodeView** A number input view which like input password in alipay or wechat pay. 支付密码输入view GET   
   项目地址：[https://github.com/linkaipeng/NumberCodeView](https://github.com/linkaipeng/NumberCodeView)    
   ![示例图](https://github.com/linkaipeng/NumberCodeView/raw/master/screenshots/screenshot_number.png) ![示例图](https://raw.githubusercontent.com/linkaipeng/NumberCodeView/master/screenshots/screenshot_password.png)    

7. **DropDownMenu** 一个实用的多条件筛选菜单  
   项目地址：[https://github.com/dongjunkun/DropDownMenu](https://github.com/dongjunkun/DropDownMenu)  
   ![示例图](https://raw.githubusercontent.com/dongjunkun/DropDownMenu/master/art/simple.gif)    

8. **MagicProgressWidget**  MagicProgressCircle & MagicProgressBar   
   项目地址：[https://github.com/lingochamp/MagicProgressWidget](https://github.com/lingochamp/MagicProgressWidget)  
   项目文档：[http://blog.dreamtobe.cn/2015/12/13/magic_progress_widget/](http://blog.dreamtobe.cn/2015/12/13/magic_progress_widget/)    ![示例图](https://github.com/lingochamp/MagicProgressWidget/raw/master/art/demo.gif)  

9. **LabelView** 一个简单的标签控件 支持自定义 文字大小（textSize）， 间距（labelTopPadding）， 背景色（backgroundColor）， 和方向（direction）等    
   项目地址：[https://github.com/corerzhang/LabelView](https://github.com/corerzhang/LabelView)  
   ![示例图](https://github.com/corerzhang/LabelView/raw/master/screenshots/Screenshot_02.png)  

10. **openalpr-android** Android Automatic License Plate Recognition library (http://www.openalpr.com) ported for android. 一个车牌识别lib  
   项目地址：[https://github.com/SandroMachado/openalpr-android](https://github.com/SandroMachado/openalpr-android)  
   ![示例图](https://github.com/SandroMachado/openalpr-android/blob/master/images/screencast.gif)  

11. **Toro** Video List by RecyclerView made simple. Auto play/pause supported with smart caching last playing position.  
   项目地址：[https://github.com/eneim/Toro](https://github.com/eneim/Toro)  
   ![1](https://github.com/eneim/Toro/blob/master/art/sample_1.gif) ![2](https://github.com/eneim/Toro/blob/master/art/sample_2.gif) ![3](https://github.com/eneim/Toro/blob/master/art/sample_4.gif) ![4](https://github.com/eneim/Toro/blob/master/art/sample_5.gif) ![5](https://github.com/eneim/Toro/blob/master/art/sample_3.gif)    

12. **SmallBang** twitter like animation for any view :heartbeat:  
   项目地址：[https://github.com/hanks-zyh/SmallBang](https://github.com/hanks-zyh/SmallBang)  
   ![1](https://github.com/hanks-zyh/SmallBang/blob/master/screenshots/demo.gif)  

13. **ToggleDrawable** Easy drawable animation using beziers curves.  
   项目地址：[https://github.com/renaudcerrato/ToggleDrawable](https://github.com/renaudcerrato/ToggleDrawable)  
   ![1](https://vid.me/TjJV)  

14. **DemoProgressViewsLibApp**  Small sample app with examples of use ProgressViews library with custom Progress bars in different shapes.  一个优质进度条集合  
   项目地址：[https://github.com/natasam/DemoProgressViewsLibApp](https://github.com/natasam/DemoProgressViewsLibApp)  
   ![1](https://github.com/natasam/DemoProgressViewsLibApp/blob/master/screenshots/Screenshot_2015-12-13-17-36-48.png) ![2](https://github.com/natasam/DemoProgressViewsLibApp/blob/master/screenshots/Screenshot_2015-12-13-18-23-10.png) ![3](https://github.com/natasam/DemoProgressViewsLibApp/blob/master/screenshots/Screenshot_2015-12-13-15-56-38.png) ![4](https://github.com/natasam/DemoProgressViewsLibApp/blob/master/screenshots/Screenshot_2015-12-14-01-12-09.png)  

15. **CreditCardView**  CreditCardView is a rich UX custom view to accomodate Credit Cards / Debit Cards while handling payment systems. The library consists of  银行卡View  
   项目地址：[https://github.com/cooltechworks/CreditCardView](https://github.com/cooltechworks/CreditCardView)  
   ![1](https://camo.githubusercontent.com/4c63460b76b63258113c9a094bb7535c43090f5c/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3438343035372f73637265656e73686f74732f323137373130352f636865636b6f75745f67656e657269632e676966)  

16. **HFRecyclerView** Add Header and/or Footer in your RecyclerView in the simplest way possible.  带header,footer的RecyclerView  
   项目地址：[https://github.com/lopspower/HFRecyclerView](https://github.com/lopspower/HFRecyclerView)  
   ![1](https://github.com/lopspower/HFRecyclerView/blob/master/preview/preview.gif)  

17. **InstagRealm** 一个android应用搭建lib集合  InstagRealm is a sample Android application, which shows you how to integrate some of the most popular Android libraries together such as Realm, Royal, RecyclerView, CardView, Retrofit, Fresco, EventBus, Butterknife, Material Dialog and Logger.  
   项目地址：[1](https://github.com/TheFinestArtist/InstagRealm/blob/master/art/instagrealm_a_400.png)  

18. **android-shape-imageview** Custom shaped android imageview components  一个优秀图片裁剪view  
   项目地址：[https://github.com/siyamed/android-shape-imageview](https://github.com/siyamed/android-shape-imageview)  
   ![1](https://github.com/siyamed/android-shape-imageview/blob/master/images/all-samples.png)  

19. **Android-SpinKit** Android loading animations  又一个漂亮loading 集合  
   项目地址：[https://github.com/ybq/Android-SpinKit](https://github.com/ybq/Android-SpinKit)  
   ![1](https://raw.githubusercontent.com/ybq/AndroidSpinKit/master/art/screen.gif)  

20. **LuseenBottomNavigation**  Material Bottom Navigation  
   项目地址：[https://github.com/armcha/LuseenBottomNavigation](https://github.com/armcha/LuseenBottomNavigation)  
   ![1](https://github.com/armcha/LuseenBottomNavigation/blob/master/ScreenShots/gifView2.gif)  
   
### Android 性能检测  
1. **leakcanary** A memory leak detection library for Android and Java. 优秀OOM检测工具  
   项目地址：[https://github.com/square/leakcanary](https://github.com/square/leakcanary)  
   ![1](https://github.com/square/leakcanary/blob/master/assets/screenshot.png)  

2. **AppCrashTracker**  Its a kind of toolkit to track the exception arising in the application and it will generate a json and can upload in your server using your own post url.  
   项目地址：[https://github.com/macroday/AppCrashTracker](https://github.com/macroday/AppCrashTracker)  
   

> Input
ACT.init(this,MainActivity.class);
Output
"Package_Name" : com.example.act_sample,
"VM_Max_Heap_Size" : 9.3 MB,
"VM_free_Heap_Size" : 64 MB,
"VM_Heap_Size" : 9.8 MB,
"Internal_Memory_Size" : 503.4 MB,
"Internal_Free_Space" : 100.3 MB,
"Device_Orientation" : Portrait,
"Screen_Layout" : Normal Screen,
"SDCard_Status" : Mounted,
"External_Free_Space" : 1.8 GB,
"Battery_Percentage" : 100,
"Device_IsRooted" : false,
"Network_Mode" : Wifi,
"Battery_Charging_Via" : USB,
"Native_Allocated_Size" : 2 MB,
"External_Memory_Size" : 7.4 GB,
"Allocated_VM_Size" : 482.1 kB,
"Brand" : Google Nexus,
"Model" : Nexus 5,
"Product" : Nexus 5,
"Device" : 5x,
"Message" : Unable to start activity ComponentInfo{com.example.act_sample\/com.example.act_sample.MainActivity}: java.lang.NumberFormatException: Invalid int: \"asdf\",
"Incremental" : eng.terry.1365412624,
"Height" : 854,
"SDK" : 16,
"Release" : 4.1.1,
"Localized_Message" : Unable to start activity ComponentInfo{com.example.act_sample\/com.example.act_sample.MainActivity}: java.lang.NumberFormatException: Invalid int: \"asdf\",
"Tablet" : false,
"Class" : MainActivity,
"App_Version" : 1.0,
"Width" : 480,
"Stack_Trace" : java.lang.RuntimeException: Unable to start activity ComponentInfo{com.example.act_sample\/com.example.act_sample.MainActivity}: 
java.lang.NumberFormatException: Invalid int: \"asdf\"
android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2184)
android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2211)
android.app.ActivityThread.access$600(ActivityThread.java:149)
android.app.ActivityThread$H.handleMessage(ActivityThread.java:1300)
android.os.Handler.dispatchMessage(Handler.java:99)
android.os.Looper.loop(Looper.java:153)
android.app.ActivityThread.main(ActivityThread.java:5086)
java.lang.reflect.Method.invokeNative(Native Method)
java.lang.reflect.Method.invoke(Method.java:511)
com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:821)
com.android.internal.os.ZygoteInit.main(ZygoteInit.java:584)
dalvik.system.NativeStart.main(Native Method)
Caused by: java.lang.NumberFormatException: Invalid int: \"asdf\"
java.lang.Integer.invalidInt(Integer.java:138)
java.lang.Integer.parse(Integer.java:375)
java.lang.Integer.parseInt(Integer.java:366)
java.lang.Integer.parseInt(Integer.java:332)
com.example.act_sample.MainActivity.onCreate(MainActivity.java:17)
android.app.Activity.performCreate(Activity.java:5020)
android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1080)
android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2148)
... 11 more,
"Cause" : java.lang.NumberFormatException: Invalid int: \"asdf\"
"Country" : India









