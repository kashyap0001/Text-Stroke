# Text-Stroke

## How to add dependency?
This library is not released in Maven Central, but instead you can use [JitPack](https://jitpack.io)

add remote maven url in `allprojects.repositories`

```groovy
allprojects {
	repositories {
		maven { url "https://jitpack.io" }
	}
}
```

then add a library dependency

```groovy
dependencies {
	 implementation 'com.github.kashyap0001:Text-Stroke:1.0.1'
}
```

## How to use :-
```
<com.swihoc.lib_textstroke.TextStroke
        app:outlineSize="5dp"
        app:outlineColor="@color/colorPrimary"
        ...
        android:layout_width="match_parent"
        android:layout_height="match_parent"></com.swihoc.lib_textstroke.TextStroke>

```

### if belowed code are not displaying in xml then copy from here
```
	app:outlineSize="5dp"
	app:outlineColor="@color/colorPrimary"
```


# Screenshots:-
### Output
![Text with stroke image](https://github.com/kashyap0001/Text-Stroke/blob/master/Screenshot_20200319-104539.jpg)
