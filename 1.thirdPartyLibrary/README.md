<h3>Third Party Library</h3>
<p>1. retrofit</p>

```php
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    implementation 'com.squareup.okhttp3:okhttp:4.9.1'
    implementation 'com.squareup.retrofit2:converter-scalars:2.1.0'
```
<p>2. Glide</p>

```php
    implementation 'com.github.bumptech.glide:glide:4.13.0'
    kapt 'com.github.bumptech.glide:compiler:4.13.0'
```
<p>3. Circle ImageView</p>

```php
    implementation 'de.hdodenhof:circleimageview:3.1.0'
```


<h3>Android Jetpack</h3>
<p>101. Coroutines kotlin 線程</p>

```php
    implementation "org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.2"
    implementation "org.jetbrains.kotlinx:kotlinx-coroutines-core:1.6.2"
    implementation "org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.6.2"
```
<p>102. DataStore</p>

```php
    implementation "androidx.datastore:datastore-preferences:1.0.0"
    implementation "androidx.datastore:datastore-preferences-core:1.0.0"
```
<p>103. Paging3</p>

```php
    implementation "androidx.paging:paging-runtime:3.1.1"
    implementation "androidx.paging:paging-guava:3.1.1"
    implementation "androidx.paging:paging-rxjava2:3.1.1"
    testImplementation "androidx.paging:paging-common:3.1.1"
```
<p>104. WorkManger</p>

```php
    def work_version = "2.7.1"
    implementation "androidx.work:work-runtime-ktx:$work_version"
    implementation "androidx.work:work-rxjava2:$work_version"
    implementation "androidx.work:work-gcm:$work_version"
    implementation "androidx.work:work-multiprocess:$work_version"
    implementation "androidx.hilt:hilt-work:1.0.0"
    kapt "androidx.hilt:hilt-compiler:1.0.0"
    androidTestImplementation "androidx.work:work-testing:$work_version"
```

<p>105. Navigation</p>

```php
   def nav_version = "2.5.1"
   implementation "androidx.navigation:navigation-fragment:$nav_version"
   implementation "androidx.navigation:navigation-ui:$nav_version"
```
<p>106. Hilt</p>

```php
    implementation "com.google.dagger:hilt-android:2.42"
    kapt "com.google.dagger:hilt-android-compiler:2.42"
    kapt 'androidx.hilt:hilt-compiler:1.0.0'
    kapt 'com.google.dagger:hilt-compiler:2.42'
    testImplementation 'com.google.dagger:hilt-android-testing:2.38.1'
    kaptTest 'com.google.dagger:hilt-android-compiler:2.42'
    androidTestImplementation 'com.google.dagger:hilt-android-testing:2.38.1'
    kaptAndroidTest 'com.google.dagger:hilt-android-compiler:2.42'
```
<p>107. Room</p>

```php
    def room_version = "2.4.2"
    implementation "androidx.room:room-runtime:$room_version"
    implementation "androidx.room:room-ktx:$room_version"
    kapt "androidx.room:room-compiler:$room_version"
    androidTestImplementation "androidx.room:room-testing:$room_version"
```




