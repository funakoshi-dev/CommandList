Fixes # .

## Changes proposed in this pull request:
-
-
<!-- SDKリリース用 -->
### 関連PR / draft
- [wiki]()
- [sample]()
- [draft]()

## Tests:
### Environment
- Xcode (vX.Y.Z)
- Device
  - iPhone (iOS X.Y)
- Simulator
  - iPhone (iOS X.Y)

### How to / result
- [ ] ローカル環境にて自動テストが全て正常に完了することを確認
  - UnitTest
  - UITest
- [ ] [サンプルアプリ](https://github.com/fan-ADN/nendSDK-iOS-source/tree/master/Example)で各広告フォーマットの表示、クリック、デリゲートメソッド呼び出しに問題がないことを確認
 <!-- SDKリリース用 -->
- [ ] 公開中のサンプルを使用して組み込み確認を実施
  - 直接組み込み、cocoaPods経由の組み込みを行い正常に動作することを確認
  - 各広告フォーマットの表示、クリック、デリゲートメソッド呼び出しに問題がないことを確認
- [ ] アーカイブビルドが正常に行えること
  - AdHoc用に .ipa ファイルを出力し、実機にインストール＆動作に問題がないこと
  - `lipo -info` でNendAdに i386 armv7 x86_64 arm64 が含まれていること
- [ ] バイナリが正常にアップロード可能であること
  - Xcodeを使用してバイナリのアップロードが正常に行えることを確認

## Review:
### Point of view
-
-
-


[please check sdk]
[please check podspec]

[please check banner]
[please check interstitial]
[please check nativead]
[please check fullboard]
[please check video]
[please check nativevideoad]

[please check legacy sdk]

[please check capture objc]
[please check capture swift]
