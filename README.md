# awesome-android-performance
 This is a  list of awesome Android tutorials, videos and tools for performance optimization

---
## View
#### Google Official Videos
+ [Double Layout Taxation Android Performance Patterns Season 3 ep8](https://www.youtube.com/watch?v=dB3_vgS-Uqo&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=25) - fix layout problems

#### Others
+ [Infamous ViewHolder Pattern](https://sriramramani.wordpress.com/2012/07/25/infamous-viewholder-pattern/) - ViewHolder pattern in ListView
+ [View Reduction](https://sriramramani.wordpress.com/2013/03/25/view-reduction/) - use Compound Drawables  to increase performance
+ [Improving Comment Rendering on Android](https://engineering.instagram.com/improving-comment-rendering-on-android-a77d5db3d82e) - Instagram's post on TextView Performance
+ [Custom ViewGroups](https://sriramramani.wordpress.com/2015/05/06/custom-viewgroups/) - a Facebook Engineer's artcile on Custom ViewGroup to increase performance

## WebView
+ [Why Use Crosswalk?](https://software.intel.com/en-us/xdk/docs/why-use-crosswalk-for-android-builds) - use crosswalk for better performance, especiallly for android version below4.4
+ [Enhance webView performance](http://stackoverflow.com/questions/3652583/enhance-webview-performance-should-be-the-same-performance-as-native-web-browse) - disable the WebView cache to make WebView much faster.
+ [Supercharging the Android WebView](https://medium.com/myntra-engineering/leveraging-native-power-in-webview-105d248fe71) - cache critical assets that drastically reduce the load time.

#### Tools
+ [crosswalk-cordova-android](https://github.com/crosswalk-project/crosswalk-cordova-android) — An app runtime based on Chromium/Blink.

## Graphics
+ [Android 3.0 Hardware Acceleration](http://android-developers.blogspot.com/2011/03/android-30-hardware-acceleration.html)
+ [Debug Overdraw](https://developer.android.com/tools/performance/debug-gpu-overdraw/index.html) - debug overdraw
+ [Android Performance Case Study](http://www.curious-creature.com/docs/android-performance-case-study-1.html) - Debug Performance use `gfxinfo` systrace and `show GPU Overdraw ` `HierarchyViewer` `OpenGL traces`
+ [Android Performance Case Study Follow-up](http://www.curious-creature.com/2015/03/25/android-performance-case-study-follow-up/) - Use `OpenGL traces` and UUI problems caused by transparency
+ [Hardware Acceleration](http://developer.android.com/guide/topics/graphics/hardware-accel.html#layers)
+ [Optimizing Hardware Layers](http://www.curious-creature.com/2013/09/13/optimizing-hardware-layers/)
+ [Graphics Performance](https://storage.googleapis.com/androiddevelopers/android_developers_backstage/ADB%2031%20Graphics%20Performance.mp3) - Podcasts on Android Performance
+ [Hardware Acceleration Animation](http://blog.danlew.net/2015/10/20/using-hardware-layers-to-improve-animation-performance/) - Using hardware layers to improve Android animation performance,

#### Tools
+ [Analyzing UI Performance with Systrace](http://developer.android.com/intl/zh-cn/tools/debugging/systrace.html)
+ [Optimizing Your UI](http://developer.android.com/intl/zh-cn/tools/debugging/debugging-ui.html) - HierarchyViewer Usage
+ [Introduction to Systrace](http://developer.android.com/intl/zh-cn/tools/debugging/debugging-ui.html)

## Bitmaps
+ [Loading Large Bitmaps Efficiently](http://developer.android.com/training/displaying-bitmaps/load-bitmap.html#load-bitmap)
+ [Bitmap quality, banding and dithering](http://www.curious-creature.com/2010/12/08/bitmap-quality-banding-and-dithering/)
+ [Android: bitmaps, textures and pre-multiplied pixels](https://plus.google.com/+ChetHaase/posts/ef6Deey6xKA)
+ [Testing Display Performance](https://developer.android.com/preview/testing/performance.html)


## Memory
#### Google official videos
+ [Memory Performance 101](https://www.youtube.com/watch?v=OrLEoIsMIAc&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=59)
+ [Android Performance Patterns: Tool - Memory Monitor
](https://www.youtube.com/watch?v=7ls28uGMBEs&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=63) - introducing Memory monitor and Memory heap tool
+ [Android Performance Patterns: Performance Cost of Memory Leaks](https://www.youtube.com/watch?v=h7qHsk1nWKI&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=62) - on memory leaks
+ [Garbage Collection in Android](https://www.youtube.com/watch?v=pzfzz505Uo&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=61)
+ [Memory Churn and Performance](https://www.youtube.com/watch?v=McAvq5SkeTk&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=60)
+ [Avoiding Allocations in onDraw](https://www.youtube.com/watch?v=HAK5acHQ53E&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=37)
+ [Android内存优化之OOM](http://hukai.me/android-performance-oom/)

#### others
+ [Investigating Your RAM Usage](http://developer.android.com/intl/zh-cn/tools/debugging/debugging-memory.html)
+ [The truth about Preventative Optimizations](https://medium.com/google-developers/the-truth-about-preventative-optimizations-ccebadfd3eb5) - You  can find some useful things from the links.
+ [A small leak will sink a great ship](https://corner.squareup.com/2015/08/a-small-leak.html)
+ [LeakCanary](https://github.com/square/leakcanary) A memory leak detection library for Android and Java.
+ [Android内存泄露案例分析](http://www.csdn.net/article/2015-09-07/2825631)
+ [Tips for Optimizing Android Application Memory Usage](https://software.intel.com/en-us/android/articles/tips-for-optimizing-android-application-memory-usage) - Tips
+ [Android memory and performance optimization - Tutorial](http://www.vogella.com/tutorials/AndroidApplicationOptimization/article.html)
+ [Building Memory-efficient Java Applications](http://www.cs.virginia.edu/kim/publicity/pldi09tutorials/memory-efficient-java-tutorial.pdf)
+ [How to Leak a Context: Handlers & Inner Classes](http://www.androiddesignpatterns.com/2013/01/inner-class-handler-memory-leak.html)
+ [Improving Facebook's performance on Android with FlatBuffers](https://code.facebook.com/posts/872547912839369/improving-facebook-s-performance-on-android-with-flatbuffers/)

#### Tools for improving memory performnace
+ [YourKit](https://www.yourkit.com/java/profiler/) - Performance and Memory Java Profile
+ [MAT](https://eclipse.org/mat/) - Memory Analysis tool for Java
+ [Allocation Tracker](http://developer.android.com/intl/zh-cn/tools/debugging/ddms.html#alloc)

## Concurrency
+ [The Zen of IntentService. (Android Performance Patterns Season 5 ep7)](https://www.youtube.com/watch?v=9FweabuBi1U&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&index=70) - Talked about IntentServices, AsyncTasks, HandlerThread in the background thread.


## Battery
+ [Optimizing Battery Life](https://developer.android.com/training/monitoring-device-state/index.html) - Android's official tutorial for Battery Optimization

## Others
+ [SMP Primer for Android](http://developer.android.com/intl/zh-cn/training/articles/smp.html)
+ [JNI](http://developer.android.com/intl/zh-cn/training/articles/perf-jni.html)
### Network
###### Google Official
+ [Optimizing Network Request Frequencies (Android Performance Patterns Season 4 ep2)
Android Developers](https://www.youtube.com/watch?v=nDHeuEM30ks&list=PLOU2XLYxmsIKEOXh5TwZEv89aofHzNCiu&index=2) - push instead pull data, sync policies and so on.
+ [Serialization performance (Android Performance Patterns Season 4 ep14)](https://www.youtube.com/watch?v=IwxIIUypnTE&index=14&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE&linkId=20302393) - use Protobuffers and FlatBuffer to improve seiralization performance
+ [Effective Network Batching (Android Performance Patterns Season 3 ep10)](https://www.youtube.com/watch?v=Ecz5WDZoJok&index=27&list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE)
###### Others
+ [Better Compression = Faster Networking - Colt McAnlis' talk from SF Android](https://newcircle.com/s/post/1754/2015/08/20/colt-mcanlis-better-compression-faster-networking)
+ [Improving UX through performance](https://raw.githubusercontent.com/Juude/awesome-android-performance/master/docs/improving_ux_through_performance.pdf) - using okhttp, Fresco,or ToFu to improve network performance
### Network Profiling Tools
+ [ARO](https://developer.att.com/application-resource-optimizer/get-aro/download) - Use this free diagnostic tool to improve your app's battery life, data usage, and responsiveness
+ [Network Monitor in Android Studio](http://developer.android.com/intl/zh-cn/tools/help/am-network.html)


# Article Videos Tools and others that cover multiple topics
## Performance Test
+ [Testing Performance of Mobile Apps - Part 1: How Fast Can Angry Birds Run?](http://www.methodsandtools.com/archive/mobileloadtesting.php)

## Articles
+ [Performance Tuning On Android](http://blog.venmo.com/hf2t3h4x98p5e13z82pl8j66ngcmry/performance-tuning-on-android) - Venmo's experience on UI performance optimization
+ [Best Practices for Performance](http://developer.android.com/training/best-performance.html) - Android Official Training on Performance
+ [Developing for Android](https://medium.com/google-developers/developing-for-android-ix-tools-375134af1098) - Chet Haase's series,including Memory,Storage, UI Performance
+ [Detect and Resolve Performance Problems on Android](http://code.tutsplus.com/tutorials/detect-and-resolve-performance-problems-on-android--cms-24058) - Use multiple ways to detect and fix Android Performance Problems
+ [Performance Tips](http://hsc.com/Blog/Best-Practices-For-Memory-Optimization-on-Android-1) - Android's Official Perf tips
+ [Facebook Engineering blogs tagged android](https://code.facebook.com/posts/android/) - Including many articles on performance

# Tools
+ [Developing for Android IXTools](https://medium.com/google-developers/developing-for-android-ix-tools-375134af1098)
+ [Performance Profiling Tools](https://developer.android.com/tools/performance/index.html) - Performance Tools
+ [StrictMode](http://developer.android.com/intl/zh-cn/reference/android/os/StrictMode.html) - Debug Util Class for  etection for Storage, Memory and others.
+ [Probe](https://github.com/EverythingMe/probe) - Android performance instrumentation tool, comparing application vital signs (CPU usage, memory utilization, number of threads, disk usage, etc.) across app versions, detecting performace regressions.
+ [BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx) - make performance bottleneck detection easily when app blocked
+ [DroidTelescope](https://github.com/zkwlx/DroidTelescope) - detect performance bolck

## Videos
+ [Android Performance Patterns](https://www.youtube.com/playlist?list=PLOU2XLYxmsIKEOXh5TwZEv89aofHzNCiu) - Google's official Video about Android Performance
+ [Android Performance](https://www.udacity.com/course/viewer#!/c-ud825/l-3753178711/m-3766928782) - Udacity's Video Series
+ [UI Performance](https://realm.io/news/360andev-brenda-cook-optimizing-profiling-ui-performance-android-ux/) - Optimizing and Profiling UI Performance

## Codes
+ [udacity render example](https://github.com/udacity/ud825-render)
+ [leakcanary](https://github.com/square/leakcanary) - leakcanary source codes

## People you should follow(their work contribute to almost all of this list)
+ [Colt McAnlis](https://twitter.com/duhroach) - Instructor of the Video at Udacity and Youtube
+ [Chet Haase](https://twitter.com/chethaase) - Author of the [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) series
+ [Romain Guy](https://twitter.com/romainguy) - former developer of android ui framework team
+ [胡凯](hukai.me) - 翻译了包括Google官方视频的许多andorid性能优化的资料
