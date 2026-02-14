# 鸿蒙化适配

## 编译

> flutter版本: 3.35

```shell
flutter create --platforms ohos .
flutter clean && flutter pub get
flutter pub run build_runner build --delete-conflicting-outputs
flutter build hap --profile
```
