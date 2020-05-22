# code

```javascript
wx.getSystemInfo({
  success (res) {//接口调用成功的回调函数
    console.log(res)
  },
  fail(res){//接口调用失败的回调函数
    console.log(res)
  },
  complete(e){//接口调用结束的回调函数（调用成功、失败都会执行）
    console.log(e)
  }
})
```

# result

```
SDKVersion: "2.11.0"
batteryLevel: 100
benchmarkLevel: 1
brand: "devtools"
deviceOrientation: "portrait"
devicePixelRatio: 3
errMsg: "getSystemInfo:ok"
fontSizeSetting: 16
language: "zh_CN"
model: "iPhone X"
pixelRatio: 3
platform: "devtools"
safeArea: {right: 375, bottom: 812, left: 0, top: 44, width: 375, …}
screenHeight: 812
screenWidth: 375
statusBarHeight: 44
system: "iOS 10.0.1"
version: "7.0.4"
windowHeight: 724
windowWidth: 375
```
