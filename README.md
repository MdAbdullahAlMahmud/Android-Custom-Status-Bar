# Android-Custom-Status-Bar
This library will help to to customize your activity status bar as much as you want . Give a star on my library , if you find it helpful

## Overview
- Set Transparent Status bar
- Set Icon color of Transparent Status bar (Blace/White)
- set any color of status bar 
- change the icon color of status bar according to your color
- make full screen status bar  
---
## In order to use this library in your android project

Step 1. Add the JitPack repository to your build file
Add it to your build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
Step 2. Add the dependency on your app module gradle
```gradle
dependencies {
	    implementation 'com.github.MdAbdullahAlMahmud:Android-Custom-Status-Bar:v1.0.1'
}
```

## How to use
###  Custom status bar color 
`setCustomStatusColor(Activity activity, int statusBarColor, boolen isIconColorBlack)`

write before  `setContentView()` such as :


``` java

 CustomStatusBar.setCustomStatusColor(this,R.color.design_default_color_error,false);
        setContentView(R.layout.activity_main);
```
###  Transparent status bar 
`transparentStatusBar(Activity activity)`

`transparentStatusBarWithIcon(Activity activity, boolen isIconBlack)`

write before  `setContentView()` such as :


``` java

 CustomStatusBar.transparentStatusBar(this);
        setContentView(R.layout.activity_main);
```
OR
``` java

 CustomStatusBar.transparentStatusBarWithIcon(this, true);
        setContentView(R.layout.activity_main);
```
###  Make Full Screem 
`.makeFullScreen(Activity activity)`

write before  `setContentView()` such as :


``` java

 CustomStatusBar.makeFullScreen(this);
        setContentView(R.layout.activity_main);
```
### Preview
<img src="https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-05%20(2).jpg" height="300">
![Asset 1](https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-05%20(2).jpg) 
![Asset 2](https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-05.jpg)
![Asset 3](https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-06%20(2).jpg)
![Asset 4](https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-06%20(3).jpg) 
![Asset 5](https://raw.githubusercontent.com/MdAbdullahAlMahmud/Android-Custom-Status-Bar/master/photo_2021-07-15_18-09-06.jpg)
