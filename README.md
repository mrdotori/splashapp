# splashapp

Splash Screen : Just splash screen

## android
1. android/app/src/main/res/ 폴더에 drawable 폴더들에 각각 이미지를 넣는다.
2. android/app/src/main/res/values 폴더의 styles.xml 화일을 보면
    ~~~(xml) 
    <item name="android:windowBackground">@drawable/launch_background</item> 
    ~~~
    이미지 화일명이 <q>launch_background</q> 이므로 이미지 화일명도 동일하게 맞춘다.
3. 128, 192, 256, 384, 512  사이즈의 정방형 이미지를 기본으로하고, mdpi(1x), hdpi(1.5x), xhdpi(2x), xxhdpi(3x), xxxhdpi(4x) 까지 5개를 각 drawable 폴더에 넣어 주면 된다.
4. 참고 이미지를 사이즈 별로 만들어 주는 사이트
    [App Icon Generator](https://appicon.co/#image-sets)


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
