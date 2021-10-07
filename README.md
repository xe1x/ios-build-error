# Steps to reproduce

Execute the following on macOS device: 
- `yarn`
- `cd ./ios`
- `pod install`
```sh
xcodebuild \
  -arch arm64 \
  -workspace IosBuildError .xcworkspace \
  -configuration Debug \
  -scheme sigo_mobile clean build
```
