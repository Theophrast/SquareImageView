![logo](https://github.com/Theophrast/SquareImageView/blob/master/gfx/logo/squareimageview_logo_256.png)
# SquareImageView
[![](https://jitpack.io/v/Theophrast/SquareImageView.svg)](https://jitpack.io/#Theophrast/SquareImageView)



## Description
Simple wrapper library for Android ImageView.
If you need an always square or rectangular Imageview, SquareImageView is for you.


![demo1](https://github.com/Theophrast/SquareImageView/blob/master/gfx/screenshots/img_demo_01.png)
![demo1](https://github.com/Theophrast/SquareImageView/blob/master/gfx/screenshots/img_demo_02.png)



----------


## How to use SquareImageView?

#### Square shaped ImageView
From xml:
```xml
    <com.theophrast.ui.widget.SquareImageView
	     android:layout_width="match_parent"
	     android:layout_height="0dp"
	     android:scaleType="centerCrop"
	     android:src="@drawable/profile_01" />
```
Check the sample for more details.

#### Different ratios
For a rectangular shaped ImageView, set the hwRatio (height:width ratio) :

![demo1](https://github.com/Theophrast/SquareImageView/blob/master/gfx/screenshots/img_demo_03.png)

```xml
    <com.theophrast.ui.widget.SquareImageView
        android:layout_width="120dp"
        android:layout_height="0dp"
        android:scaleType="centerCrop"
        android:src="@drawable/img_02"
        app:hwRatio="0.6" />
```


## Gradle dependency
Add it in your **root build.gradle** at the end of the repositories:

```groovy
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
In your project level's **build.gradle**:
```groovy
dependencies {
	...
	compile 'com.github.Theophrast:SquareImageView:1.0.1'
}
```



## License
```
Copyright 2017 Janos Jakub

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```



