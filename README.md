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
