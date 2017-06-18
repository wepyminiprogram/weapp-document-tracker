<div class="book with-summary">

<div class="head">

<div class="head_box">

# [](javascript:; "_('微信公众平台 小程序')")

<div class="header_ctrls">

*   [介绍](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=2017616)
*   [设计](https://mp.weixin.qq.com/debug/wxadoc/design/index.html?t=2017616)
*   [开发](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html?t=2017616)
*   [运营](https://mp.weixin.qq.com/debug/wxadoc/product/index.html?t=2017616)
*   [数据](https://mp.weixin.qq.com/debug/wxadoc/analysis/index.html?t=2017616)

</div>

</div>

</div>

<div class="sub_nav_box">

<div class="sub_nav_inner">

<div class="book-summary-opr" id="js-book-summary-opr"><a class="book-summary-btn"></a></div>

<div class="top_sub_nav">

<div class="top_title_wap"><span class="icon_title icon_dev"></span>

微信小程序开发文档

</div>

*   [简易教程](../)
*   [框架](../framework/MINA.html)
*   [组件](../component/)
*   [API](./)
*   [工具](../devtools/devtools.html)
*   [Q&A](../qa.html)

</div>

<div id="book-search-input" role="search">

<form><label for="search-input" class="search-icon" id="js-search-icon"></label><input type="text" id="search-input" name="search-input" placeholder="搜索"> </form>

</div>

</div>

</div>

<div class="book-summary">

<div class="book-summary-home" id="js-summary-home"><a><span class="icon_home_s icon_dev"></span><span class="s_title_2">开发文档首页</span></a></div>

<nav role="navigation">

*   [网络](api-network.html)
    *   [发起请求](network-request.html)
        *   [wx.request](network-request.html#wxrequestobject)
    *   [上传、下载](network-file.html)
        *   [wx.uploadFile](network-file.html#wxuploadfileobject)
        *   [wx.downloadFile](network-file.html#wxdownloadfileobject)
    *   [WebSocket](network-socket.html)
        *   [wx.connectSocket](network-socket.html#wxconnectsocketobject)
        *   [wx.onSocketOpen](network-socket.html#wxonsocketopencallback)
        *   [wx.onSocketError](network-socket.html#wxonsocketerrorcallback)
        *   [wx.sendSocketMessage](network-socket.html#wxsendsocketmessageobject)
        *   [wx.onSocketMessage](network-socket.html#wxonsocketmessagecallback)
        *   [wx.closeSocket](network-socket.html#wxclosesocket)
        *   [wx.onSocketClose](network-socket.html#wxonsocketclosecallback)
*   [媒体](media-picture.html)
    *   [图片](media-picture.html)
        *   [wx.chooseImage](media-picture.html#wxchooseimageobject)
        *   [wx.previewImage](media-picture.html#wxpreviewimageobject)
        *   [wx.getImageInfo](media-picture.html#wxgetimageinfoobject)
        *   [wx.saveImageToPhotosAlbum](media-picture.html#wxsaveimagetophotosalbumobject)
    *   [录音](media-record.html)
        *   [wx.startRecord](media-record.html#wxstartrecordobject)
        *   [wx.stopRecord](media-record.html#wxstoprecord)
    *   [音频播放控制](media-voice.html)
        *   [wx.playVoice](media-voice.html#wxplayvoiceobject)
        *   [wx.pauseVoice](media-voice.html#wxpausevoice)
        *   [wx.stopVoice](media-voice.html#wxstopvoice)
    *   [音乐播放控制](media-background-audio.html)
        *   [wx.getBackgroundAudioPlayerState](media-background-audio.html#wxgetbackgroundaudioplayerstateobject)
        *   [wx.playBackgroundAudio](media-background-audio.html#wxplaybackgroundaudioobject)
        *   [wx.pauseBackgroundAudio](media-background-audio.html#wxpausebackgroundaudio)
        *   [wx.seekBackgroundAudio](media-background-audio.html#wxseekbackgroundaudioobject)
        *   [wx.stopBackgroundAudio](media-background-audio.html#wxstopbackgroundaudio)
        *   [wx.onBackgroundAudioPlay](media-background-audio.html#wxonbackgroundaudioplaycallback)
        *   [wx.onBackgroundAudioPause](media-background-audio.html#wxonbackgroundaudiopausecallback)
        *   [wx.onBackgroundAudioStop](media-background-audio.html#wxonbackgroundaudiostopcallback)
    *   [背景音频播放管理](getBackgroundAudioManager.html)
        *   [wx.getBackgroundAudioManager](getBackgroundAudioManager.html)
    *   [音频组件控制](api-audio.html)
        *   [wx.createAudioContext](api-audio.html#wxcreateaudiocontextaudioid)
    *   [视频](media-video.html)
        *   [wx.chooseVideo](media-video.html#wxchoosevideoobject)
        *   [wx.saveVideoToPhotosAlbum](media-video.html#wxsavevideotophotosalbumobject)
    *   [视频组件控制](api-video.html)
        *   [wx.createVideoContext](api-video.html#wxcreatevideocontextvideoid)
*   [文件](file.html)
    *   [wx.saveFile](file.html#wxsavefileobject)
    *   [wx.getSavedFileList](file.html#wxgetsavedfilelistobject)
    *   [wx.getSavedFileInfo](file.html#wxgetsavedfileinfoobject)
    *   [wx.removeSavedFile](file.html#wxremovesavedfileobject)
    *   [wx.openDocument](file.html#wxopendocumentobject)
*   [数据缓存](data.html)
    *   [wx.setStorage](data.html#wxsetstorageobject)
    *   [wx.setStorageSync](data.html#wxsetstoragesynckeydata)
    *   [wx.getStorage](data.html#wxgetstorageobject)
    *   [wx.getStorageSync](data.html#wxgetstoragesynckey)
    *   [wx.getStorageInfo](data.html#wxgetstorageinfoobject)
    *   [wx.getStorageInfoSync](data.html#wxgetstorageinfosync)
    *   [wx.removeStorage](data.html#wxremovestorageobject)
    *   [wx.removeStorageSync](data.html#wxremovestoragesynckey)
    *   [wx.clearStorage](data.html#wxclearstorage)
    *   [wx.clearStorageSync](data.html#wxclearstoragesync)
*   [位置](location.html)
    *   [获取位置](location.html)
        *   [wx.getLocation](location.html#wxgetlocationobject)
        *   [wx.chooseLocation](location.html#wxchooselocationobject)
    *   [查看位置](location.html#wxopenlocationobject)
        *   [wx.openLocation](location.html#wxopenlocationobject)
    *   [地图组件控制](api-map.html)
        *   [wx.createMapContext](api-map.html#wxcreatemapcontextmapid)
*   [设备](systeminfo.html)
    *   [系统信息](systeminfo.html)
        *   [wx.getSystemInfo](systeminfo.html#wxgetsysteminfoobject)
        *   [wx.getSystemInfoSync](systeminfo.html#wxgetsysteminfosync)
        *   [wx.canIUse](api-caniuse.html)
    *   [网络状态](device.html)
        *   [wx.getNetworkType](device.html#wxgetnetworktypeobject)
        *   [wx.onNetworkStatusChange](device.html#wxonnetworkstatuschangecallback)
    *   [加速度计](accelerometer.html)
        *   [wx.onAccelerometerChange](accelerometer.html#wxonaccelerometerchangecallback)
        *   [wx.startAccelerometer](accelerometer.html#wxstartaccelerometerobject)
        *   [wx.stopAccelerometer](accelerometer.html#wxstopaccelerometerobject)
    *   [罗盘](compass.html)
        *   [wx.onCompassChange](compass.html#wxoncompasschangecallback)
        *   [wx.startCompass](compass.html#wxstartcompassobject)
        *   [wx.stopCompass](compass.html#wxstopcompassobject)
    *   [拨打电话](phonecall.html)
        *   [wx.makePhoneCall](phonecall.html#wxmakephonecallobject)
    *   [扫码](scancode.html)
        *   [wx.scanCode](scancode.html#wxscancodeobject)
    *   [剪贴板](clipboard.html)
        *   [wx.setClipboardData](clipboard.html#wxsetclipboarddataobject)
        *   [wx.getClipboardData](clipboard.html#wxgetclipboarddataobject)
    *   [蓝牙](bluetooth.html)
        *   [wx.openBluetoothAdapter](bluetooth.html#wxopenbluetoothadapterobject)
        *   [wx.closeBluetoothAdapter](bluetooth.html#wxclosebluetoothadapterobject)
        *   [wx.getBluetoothAdapterState](bluetooth.html#wxgetbluetoothadapterstateobject)
        *   [wx.onBluetoothAdapterStateChange](bluetooth.html#wxonbluetoothadapterstatechangecallback)
        *   [wx.startBluetoothDevicesDiscovery](bluetooth.html#wxstartbluetoothdevicesdiscoveryobject)
        *   [wx.stopBluetoothDevicesDiscovery](bluetooth.html#wxstopbluetoothdevicesdiscoveryobject)
        *   [wx.getBluetoothDevices](bluetooth.html#wxgetbluetoothdevicesobject)
        *   [wx.getConnectedBluetoothDevices](bluetooth.html#wxgetconnectedbluetoothdevicesobject)
        *   [wx.onBluetoothDeviceFound](bluetooth.html#wxonbluetoothdevicefoundcallback)
        *   [wx.createBLEConnection](bluetooth.html#wxcreatebleconnectionobject)
        *   [wx.closeBLEConnection](bluetooth.html#wxclosebleconnectionobject)
        *   [wx.getBLEDeviceServices](bluetooth.html#wxgetbledeviceservicesobject)
        *   [wx.getBLEDeviceCharacteristics](bluetooth.html#wxgetbledevicecharacteristicsobject)
        *   [wx.readBLECharacteristicValue](bluetooth.html#wxreadblecharacteristicvalueobject)
        *   [wx.writeBLECharacteristicValue](bluetooth.html#wxwriteblecharacteristicvalueobject)
        *   [wx.notifyBLECharacteristicValueChange](bluetooth.html#wxnotifyblecharacteristicvaluechangeobject)
        *   [wx.onBLEConnectionStateChange](bluetooth.html#wxonbleconnectionstatechangecallback)
        *   [wx.onBLECharacteristicValueChange](bluetooth.html#wxonblecharacteristicvaluechangecallback)
    *   [iBeacon](iBeacon.html)
        *   [wx.startBeaconDiscovery](iBeacon.html#wxstartbeacondiscoveryobject)
        *   [wx.stopBeaconDiscovery](iBeacon.html#wxstopbeacondiscoveryobject)
        *   [wx.getBeacons](iBeacon.html#wxgetbeaconsobject)
        *   [wx.onBeaconUpdate](iBeacon.html#wxonbeaconupdatecallback)
        *   [wx.onBeaconServiceChange](iBeacon.html#wxonbeaconservicechangecallback)
    *   [屏幕亮度](device.html#wxsetscreenbrightnessobject)
        *   [wx.setScreenBrightness](device.html#wxsetscreenbrightnessobject)
        *   [wx.getScreenBrightness](device.html#wxgetscreenbrightnessobject)
    *   [振动](device.html#wxvibratelongobject)
        *   [wx.vibrateLong](device.html#wxvibratelongobject)
        *   [wx.vibrateShort](device.html#wxvibrateshortobject)
    *   [手机联系人](phone-contact.html)
        *   [wx.addPhoneContact](phone-contact.html#wxaddphonecontactobject)
*   [界面](api-react.html)
    *   [交互反馈](api-react.html)
        *   [wx.showToast](api-react.html#wxshowtoastobject)
        *   [wx.showLoading](api-react.html#wxshowloadingobject)
        *   [wx.hideToast](api-react.html#wxhidetoast)
        *   [wx.hideLoading](api-react.html#wxhideloading)
        *   [wx.showModal](api-react.html#wxshowmodalobject)
        *   [wx.showActionSheet](api-react.html#wxshowactionsheetobject)
    *   [设置导航条](ui.html)
        *   [wx.setNavigationBarTitle](ui.html#wxsetnavigationbartitleobject)
        *   [wx.showNavigationBarLoading](ui.html#wxshownavigationbarloading)
        *   [wx.hideNavigationBarLoading](ui.html#wxhidenavigationbarloading)
    *   [导航](ui-navigate.html)
        *   [wx.navigateTo](ui-navigate.html#wxnavigatetoobject)
        *   [wx.redirectTo](ui-navigate.html#wxredirecttoobject)
        *   [wx.switchTab](ui-navigate.html#wxswitchtabobject)
        *   [wx.navigateBack](ui-navigate.html#wxnavigatebackobject)
        *   [wx.reLaunch](ui-navigate.html#wxrelaunchobject)
    *   [动画](api-animation.html)
        *   [wx.createAnimation](api-animation.html#wxcreateanimationobject)
    *   [绘图](canvas/reference.html)
        *   [intro](canvas/intro.html)
        *   [coordinates](canvas/coordinates.html)
        *   [gradient](canvas/gradient.html)
        *   [reference](canvas/reference.html)
        *   [color](canvas/color.html)
        *   [wx.createCanvasContext](canvas/create-canvas-context.html)
        *   [wx.createContext](canvas/create-context.html)
        *   [wx.drawCanvas](canvas/draw-canvas.html)
        *   [wx.canvasToTempFilePath](canvas/temp-file.html)
        *   [setFillStyle](canvas/set-fill-style.html)
        *   [setStrokeStyle](canvas/set-stroke-style.html)
        *   [setShadow](canvas/set-shadow.html)
        *   [createLinearGradient](canvas/create-linear-gradient.html)
        *   [createCircularGradient](canvas/create-circular-gradient.html)
        *   [addColorStop](canvas/add-color-stop.html)
        *   [setLineWidth](canvas/set-line-width.html)
        *   [setLineCap](canvas/set-line-cap.html)
        *   [setLineJoin](canvas/set-line-join.html)
        *   [setMiterLimit](canvas/set-miter-limit.html)
        *   [rect](canvas/rect.html)
        *   [fillRect](canvas/fill-rect.html)
        *   [strokeRect](canvas/stroke-rect.html)
        *   [clearRect](canvas/clear-rect.html)
        *   [fill](canvas/fill.html)
        *   [stroke](canvas/stroke.html)
        *   [beginPath](canvas/begin-path.html)
        *   [closePath](canvas/close-path.html)
        *   [moveTo](canvas/move-to.html)
        *   [lineTo](canvas/line-to.html)
        *   [arc](canvas/arc.html)
        *   [bezierCurveTo](canvas/bezier-curve-to.html)
        *   [quadraticCurveTo](canvas/quadratic-curve-to.html)
        *   [scale](canvas/scale.html)
        *   [rotate](canvas/rotate.html)
        *   [translate](canvas/translate.html)
        *   [setFontSize](canvas/set-font-size.html)
        *   [fillText](canvas/fill-text.html)
        *   [setTextAlign](canvas/set-text-align.html)
        *   [drawImage](canvas/draw-image.html)
        *   [setGlobalAlpha](canvas/set-global-alpha.html)
        *   [save](canvas/save-restore.html)
        *   [restore](canvas/save-restore.html#restore)
        *   [draw](canvas/draw.html)
        *   [getActions](canvas/get-actions.html)
        *   [clearActions](canvas/clear-actions.html)
    *   [下拉刷新](pulldown.html)
        *   [Page.onPullDownRefresh](pulldown.html#onpulldownrefresh)
        *   [wx.stopPullDownRefresh](pulldown.html#wxstoppulldownrefresh)
*   [第三方平台](ext-api.html)
    *   [wx.getExtConfig](ext-api.html#wxgetextconfigobject)
    *   [wx.getExtConfigSync](ext-api.html#wxgetextconfigsync)
*   [开放接口](api-login.html)
    *   [登录](api-login.html)
        *   [wx.login](api-login.html#wxloginobject)
        *   [wx.checkSession](api-login.html#wxchecksessionobject)
        *   [签名加密](signature.html)
    *   [授权](authorize.html)
        *   [wx.authorize](authorize.html#wxauthorizeobject)
    *   [用户信息](open.html)
        *   [wx.getUserInfo](open.html#wxgetuserinfoobject)
    *   [微信支付](api-pay.html)
        *   [wx.requestPayment](api-pay.html#wxrequestpaymentobject)
    *   [模板消息](notice.html)
        *   [使用说明](notice.html#使用说明)
        *   [接口说明](notice.html#接口说明)
    *   [客服消息](custommsg/receive.html)
        *   [接收消息和事件](custommsg/receive.html#接收消息和事件)
            *   [文本消息](custommsg/receive.html#文本消息)
            *   [图片消息](custommsg/receive.html#图片消息)
            *   [进入会话事件](custommsg/receive.html#进入会话事件)
        *   [发送客服消息](custommsg/conversation.html)
        *   [临时素材接口](custommsg/material.html)
            *   [获取临时素材](custommsg/material.html#获取临时素材)
            *   [新增临时素材](custommsg/material.html#新增临时素材)
        *   [接入指引](custommsg/callback_help.html)
    *   [转发](share.html)
        *   [Page.onShareAppMessage](share.html#onshareappmessage)
        *   [wx.showShareMenu](share.html#wxshowsharemenuobject)
        *   [wx.hideShareMenu](share.html#wxhidesharemenuobject)
        *   [wx.updateShareMenu](share.html#wxupdatesharemenuobject)
        *   [wx.getShareInfo](share.html#wxgetshareinfoobject)
        *   [获取更多转发信息](share.html#获取更多转发信息)
        *   [页面内发起转发](share.html#页面内发起转发)
    *   [获取二维码](qrcode.html)
    *   [收货地址](address.html)
        *   [wx.chooseAddress](address.html#wxchooseaddressobject)
    *   [卡券](card.html)
        *   [wx.addCard](card.html#wxaddcardobject)
        *   [wx.openCard](card.html#wxopencardobject)
    *   [设置](setting.html)
        *   [wx.openSetting](setting.html#wxopensettingobject)
        *   [wx.getSetting](setting.html#wxgetsettingobject)
    *   [微信运动](we-run.html)
        *   [wx.getWeRunData](we-run.html#wxgetwerundataobject)
*   [数据](analysis.html)
    *   [常规分析](analysis.html)
        *   [概况](analysis.html#概况)
            *   [概况趋势](analysis.html#概况趋势)
        *   [访问分析](analysis-visit.html#访问分析)
            *   [访问趋势](analysis-visit.html#访问趋势)
            *   [访问分布](analysis-visit.html#访问分布)
            *   [访问留存](analysis-visit.html#访问留存)
            *   [访问页面](analysis-visit.html#访问页面)
        *   [用户画像](analysis-user.html)
    *   [自定义分析](analysis-report.html)
        *   [自定义数据上报](analysis-report.html)
*   [拓展接口](api-util.html)
    *   [wx.arrayBufferToBase64](api-util.html#wxarraybuffertobase64arraybuffer)
    *   [wx.base64ToArrayBuffer](api-util.html#wxbase64toarraybufferbase64)

</nav>

</div>

<div class="book-body">

<div class="body-inner">

<div class="page-wrapper" tabindex="-1" role="main">

<div class="page-inner">

<div id="book-search-results">

<div class="search-noresults">

<section class="normal markdown-section">

### wx.createAnimation(OBJECT)

创建一个动画实例[animation](#animation)。调用实例的方法来描述动画。最后通过动画实例的`export`方法导出动画数据传递给组件的`animation`属性。

**注意: `export` 方法每次调用后会清掉之前的动画操作**

**OBJECT参数说明：**

<table>

<thead>

<tr>

<th>参数</th>

<th>类型</th>

<th>必填</th>

<th>默认值</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>duration</td>

<td>Integer</td>

<td>否</td>

<td>400</td>

<td>动画持续时间，单位ms</td>

</tr>

<tr>

<td>timingFunction</td>

<td>String</td>

<td>否</td>

<td>"linear"</td>

<td>定义动画的效果</td>

</tr>

<tr>

<td>delay</td>

<td>Integer</td>

<td>否</td>

<td>0</td>

<td>动画延迟时间，单位 ms</td>

</tr>

<tr>

<td>transformOrigin</td>

<td>String</td>

<td>否</td>

<td>"50% 50% 0"</td>

<td>设置transform-origin</td>

</tr>

</tbody>

</table>

**timingFunction 有效值：**

<table>

<thead>

<tr>

<th>值</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>linear</td>

<td>动画从头到尾的速度是相同的</td>

</tr>

<tr>

<td>ease</td>

<td>动画以低速开始，然后加快，在结束前变慢</td>

</tr>

<tr>

<td>ease-in</td>

<td>动画以低速开始</td>

</tr>

<tr>

<td>ease-in-out</td>

<td>动画以低速开始和结束</td>

</tr>

<tr>

<td>ease-out</td>

<td>动画以低速结束</td>

</tr>

<tr>

<td>step-start</td>

<td>动画第一帧就跳至结束状态直到结束</td>

</tr>

<tr>

<td>step-end</td>

<td>动画一直保持开始状态，最后一帧跳到结束状态</td>

</tr>

</tbody>

</table>

    var animation = wx.createAnimation({
      transformOrigin: "50% 50%",
      duration: 1000,
      timingFunction: "ease",
      delay: 0
    })

### animation

动画实例可以调用以下方法来描述动画，调用结束后会返回自身，支持链式调用的写法。

**animation 对象的方法列表：**

样式：

<table>

<thead>

<tr>

<th>方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>opacity</td>

<td>value</td>

<td>透明度，参数范围 0~1</td>

</tr>

<tr>

<td>backgroundColor</td>

<td>color</td>

<td>颜色值</td>

</tr>

<tr>

<td>width</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

<tr>

<td>height</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

<tr>

<td>top</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

<tr>

<td>left</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

<tr>

<td>bottom</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

<tr>

<td>right</td>

<td>length</td>

<td>长度值，如果传入 Number 则默认使用 px，可传入其他自定义单位的长度值</td>

</tr>

</tbody>

</table>

旋转：

<table>

<thead>

<tr>

<th>方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>rotate</td>

<td>deg</td>

<td>deg的范围-180~180，从原点顺时针旋转一个deg角度</td>

</tr>

<tr>

<td>rotateX</td>

<td>deg</td>

<td>deg的范围-180~180，在X轴旋转一个deg角度</td>

</tr>

<tr>

<td>rotateY</td>

<td>deg</td>

<td>deg的范围-180~180，在Y轴旋转一个deg角度</td>

</tr>

<tr>

<td>rotateZ</td>

<td>deg</td>

<td>deg的范围-180~180，在Z轴旋转一个deg角度</td>

</tr>

<tr>

<td>rotate3d</td>

<td>(x,y,z,deg)</td>

<td>同[transform-function rotate3d](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate3d)</td>

</tr>

</tbody>

</table>

缩放：

<table>

<thead>

<tr>

<th style="text-align:left">方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left">scale</td>

<td>sx,[sy]</td>

<td>一个参数时，表示在X轴、Y轴同时缩放sx倍数；两个参数时表示在X轴缩放sx倍数，在Y轴缩放sy倍数</td>

</tr>

<tr>

<td style="text-align:left">scaleX</td>

<td>sx</td>

<td>在X轴缩放sx倍数</td>

</tr>

<tr>

<td style="text-align:left">scaleY</td>

<td>sy</td>

<td>在Y轴缩放sy倍数</td>

</tr>

<tr>

<td style="text-align:left">scaleZ</td>

<td>sz</td>

<td>在Z轴缩放sy倍数</td>

</tr>

<tr>

<td style="text-align:left">scale3d</td>

<td>(sx,sy,sz)</td>

<td>在X轴缩放sx倍数，在Y轴缩放sy倍数，在Z轴缩放sz倍数</td>

</tr>

</tbody>

</table>

偏移：

<table>

<thead>

<tr>

<th>方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>translate</td>

<td>tx,[ty]</td>

<td>一个参数时，表示在X轴偏移tx，单位px；两个参数时，表示在X轴偏移tx，在Y轴偏移ty，单位px。</td>

</tr>

<tr>

<td>translateX</td>

<td>tx</td>

<td>在X轴偏移tx，单位px</td>

</tr>

<tr>

<td>translateY</td>

<td>ty</td>

<td>在Y轴偏移tx，单位px</td>

</tr>

<tr>

<td>translateZ</td>

<td>tz</td>

<td>在Z轴偏移tx，单位px</td>

</tr>

<tr>

<td>translate3d</td>

<td>(tx,ty,tz)</td>

<td>在X轴偏移tx，在Y轴偏移ty，在Z轴偏移tz，单位px</td>

</tr>

</tbody>

</table>

倾斜：

<table>

<thead>

<tr>

<th>方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>skew</td>

<td>ax,[ay]</td>

<td>参数范围-180~180；一个参数时，Y轴坐标不变，X轴坐标延顺时针倾斜ax度；两个参数时，分别在X轴倾斜ax度，在Y轴倾斜ay度</td>

</tr>

<tr>

<td>skewX</td>

<td>ax</td>

<td>参数范围-180~180；Y轴坐标不变，X轴坐标延顺时针倾斜ax度</td>

</tr>

<tr>

<td>skewY</td>

<td>ay</td>

<td>参数范围-180~180；X轴坐标不变，Y轴坐标延顺时针倾斜ay度</td>

</tr>

</tbody>

</table>

矩阵变形：

<table>

<thead>

<tr>

<th>方法</th>

<th>参数</th>

<th>说明</th>

</tr>

</thead>

<tbody>

<tr>

<td>matrix</td>

<td>(a,b,c,d,tx,ty)</td>

<td>同[transform-function matrix](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix)</td>

</tr>

<tr>

<td>matrix3d</td>

<td></td>

<td>同[transform-function matrix3d](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix3d)</td>

</tr>

</tbody>

</table>

### 动画队列

调用动画操作方法后要调用 `step()` 来表示一组动画完成，可以在一组动画中调用任意多个动画方法，一组动画中的所有动画会同时开始，一组动画完成后才会进行下一组动画。step 可以传入一个跟 `wx.createAnimation()` 一样的配置参数用于指定当前组动画的配置。

**示例：**

    <view animation="{{animationData}}" style="background:red;height:100rpx;width:100rpx"></view>

    Page({
      data: {
        animationData: {}
      },
      onShow: function(){
        var animation = wx.createAnimation({
          duration: 1000,
            timingFunction: 'ease',
        })

        this.animation = animation

        animation.scale(2,2).rotate(45).step()

        this.setData({
          animationData:animation.export()
        })

        setTimeout(function() {
          animation.translate(30).step()
          this.setData({
            animationData:animation.export()
          })
        }.bind(this), 1000)
      },
      rotateAndScale: function () {
        // 旋转同时放大
        this.animation.rotate(45).scale(2, 2).step()
        this.setData({
          animationData: this.animation.export()
        })
      },
      rotateThenScale: function () {
        // 先旋转后放大
        this.animation.rotate(45).step()
        this.animation.scale(2, 2).step()
        this.setData({
          animationData: this.animation.export()
        })
      },
      rotateAndScaleThenTranslate: function () {
        // 先旋转同时放大，然后平移
        this.animation.rotate(45).scale(2, 2).step()
        this.animation.translate(100, 100).step({ duration: 1000 })
        this.setData({
          animationData: this.animation.export()
        })
      }
    })

#### bug & tip

1.  `bug`: `iOS/Android` `6.3.30` 通过 step() 分隔动画，只有第一步动画能生效

</section>

</div>

<div class="search-results">

<div class="has-results">

# <span class="search-results-count"></span>个结果 "<span class="search-query"></span>"

</div>

<div class="no-results">

# 没有找到相关内容 "<span class="search-query"></span>"

</div>

</div>

</div>

</div>

</div>

<div class="foot" id="footer">

*   [关于腾讯](http://www.tencent.com/zh-cn/index.shtml)
*   [文档中心](https://mp.weixin.qq.com/debug/wxadoc/introduction/index.html?t=1484641676&t=2017616)
*   [辟谣中心](https://mp.weixin.qq.com/cgi-bin/opshowpage?action=dispelinfo&lang=zh_CN&begin=1&count=9)
*   [客服中心](http://kf.qq.com/faq/120911VrYVrA1509086vyumm.html)
*   [联系邮箱](mailto:weixinmp@qq.com)
*   Copyright © 2012-<span id="s_copyright_year"></span> Tencent. All Rights Reserved.

</div>

</div>

[](ui-navigate.html#wxrelaunchobject)[](api-animation.html#wxcreateanimationobject)</div>

</div>