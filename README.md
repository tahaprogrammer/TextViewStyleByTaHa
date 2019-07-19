# TetxViewStyle
Hi guys , this libray for changing style of text in android Developement .
# Example 

<img alt="Card sample" width="360" height="600" src="http://mrjeandeveloper.online/s1.png" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img alt="Bar sample" width="360" height="600" src="http://mrjeandeveloper.online/s2.png" />

# Example Usage

```groovy
<com.example.textstylelibrary.TextViewStyle
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:text="Hello World!"
        app:textStyle="5"
        app:textColor="@color/colorAccent"
        app:textSize="70" />
```
# Add Library 

```groovy
dependencies {
	        implementation 'com.github.tahaprogrammer:TetxViewStyle:1.0.0'
	}
```

```groovy
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```