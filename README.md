# ViewPagerIndicator

A Simple View Pager Indicator with animations

## Gradle

* Step 1. Add the JitPack repository to your build file

```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

* Step 2. Add the dependency

```gradle
	dependencies {
	        compile 'com.github.vivchar:ViewPagerIndicator:v1.0.1'
	}
```

## Usage

* Step 1. Add to your layout

```
	<com.github.vivchar.viewpagerindicator.ViewPagerIndicator
		android:id = "@+id/view_pager_indicator"
		android:layout_width = "wrap_content"
		android:layout_height = "wrap_content"
		app:delimiterSize = "8dp"
		app:itemSize = "8dp"
		/>
```

* Step 2. Set ViewPager

``` java
		viewPagerIndicator.setupWithViewPager(mViewPager);
		viewPagerIndicator.addOnPageChangeListener(mOnPageChangeListener);
```

## License

    Copyright 2017 Vitaly Vivchar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
