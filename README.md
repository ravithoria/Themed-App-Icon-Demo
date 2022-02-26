# Themed-App-Icon-Demo - Android 13
Add the monochrome android:drawable attribute to the <adaptive-icon> element. For example, in res/mipmap-anydpi-v26/ic_launcher.xml

<adaptive-icon >
    <background android:drawable="..." />
    <foreground android:drawable="..." />
    <monochrome android:drawable="@drawable/myicon" />
</adaptive-icon>
  
Note: If android:roundIcon and android:icon are both in your manifest, you must either remove the reference to android:roundIcon or supply the monochrome icon in the drawable defined by the android:roundIcon attribute. 

<img src="https://user-images.githubusercontent.com/16267564/155836296-de527488-a5fd-46ab-97a4-83b730c3d5e4.png" width="320" height="700">  <img src="https://user-images.githubusercontent.com/16267564/155836297-19f2e404-f68f-4301-b13d-e20ffbbce56a.png" width="320" height="700">
