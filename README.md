# UniversalImageLoader

<H3>For use this</H3>

<H4>
<ol type="1">
<li>Add dependancy in build.gradle(App Level)</li>
compile 'com.nostra13.universalimageloader:universal-image-loader:1.9.5'
<li>In Manifest.xml file add name in Application Tag eg. android:name=".UILApplication"</li>
<li>In java file</li>
</ol>
</H4>
```java
ImageLoader.getInstance().displayImage(<ImageURL>, <ImageView>, DisplayImageOption.getDisplayImage(), new AnimateFirstDisplayListener());
```
