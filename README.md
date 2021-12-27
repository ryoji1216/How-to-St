# Flutter 使い方

1. Flutter Project の作成
   ```
   $ flutter create [Appの名前]
   ```
2. iOSのビルドを実行
   ```
   $ cd [Appの名前]
   $ flutter build ios
   ```
3. XcodeでSign in
   ```
   $ open ios/Runner.xcworkspace
   ```
   `Runner` -> `Signing & Capabilities` をクリック
   Team: `諒次 辻本 (Personal Team)`
   BundleIdentifier `com.ryotan.[Appの名前 (小文字)]`
   ![Xcode SS](./images/Xcode%20ScreenShot.png)
4. Simulatorを起動
   `Simulator` を右クリックして起動したい端末を選択
   ![Simulator SS](./images/Simulator%20ScreenShot.png)
5. Simulator上でアプリを実行
   ```
   $ flutter run
   ```
