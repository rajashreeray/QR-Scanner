# qr_scanner

A new Flutter application to scan QR_Code.
![](images/22.png)

### Screenshots of Application
<img src="images/33.png" width="300" height="500">
<img src="images/44.png" width="300" height="500">


### Package decription 
package name - barcode_scan

[package details](https://pub.dartlang.org/packages/barcode_scan)

package features -
* [x] Scan 2D barcodes
* [x] Scan QR codes
* [x] Control the flash while scanning
* [x] Permission handling
* [ ] Support multiple barcode libraries

### Android 
 add the permission and the activity to AndroidManifest.xml
  
  `<uses-permission android:name="android.permission.CAMERA" />`
  
  `<activity android:name="com.apptreesoftware.barcodescan.BarcodeScannerActivity"/>`
  
### Ios
  add a key and a string to Info.plist 
 
 `<key>NSCameraUsageDescription</key>`
 
  `<string>Camera permission is required for barcode scanning.</string>`
 
  
  
## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).
