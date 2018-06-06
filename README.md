# podspecs

My poor mans script for now ...

```
cd ~/.cocoapods/repos/master/Spec

find . \( -name LaunchDarkly -o -name CLTokenInputView -o -name Crashlytics -o -name Eureka -o -name Fabric -o -name Fakery -o -name GoogleAnalytics -o -name JVFloatLabeledTextField -o -name MBProgressHUD -o -name OHHTTPStubs -o -name QRCodeReaderViewController -o -name SSZipArchive -o -name WYPopoverController -o -name Starscream \) -exec mkdir -p /Users/shawnce/dev/procore/podspecs/Specs/{} \; -exec cp -R {}/ /Users/shawnce/dev/procore/podspecs/Specs/{} \;
```
