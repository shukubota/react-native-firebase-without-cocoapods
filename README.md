# react-native-firebase-without-cocoapods
pod 使わずにfirebaseと連携する

## 初期設定
```yarn global add react-native-cli```

react-native --versionで確認

yarn global binで確認したパスは通しとく

https://qiita.com/chkk525@github/items/ea1c2a110bf74efd843c
https://qiita.com/t-hiroyoshi/items/49c03456e991594c3dc0

```react-native init fbconnectApp --version 0.55.4```

バージョンを指定してinitする


``` cd fbconnectApp```
```react-native link```
```react-native run-ios```
でビルドする
