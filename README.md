# hello-world
try
i will kill all the paper tiger





PouchDB 是一个受Apache CouchDB启发的开源JavaScript数据库，旨在在浏览器中良好运行。
PouchDB是为帮助Web开发人员构建在线工作的离线应用程序而创建的。 它使应用程序能够在脱机时本地存储数据，然后在应用程序重新联机时将其与CouchDB和兼容服务器同步，从而保持用户的数据同步，无论他们下次登录到何处。
用法:
var db = new PouchDB('dbname');

db.put({
  _id: 'dave@gmail.com',
  name: 'David',
  age: 69
});

db.changes().on('change', function() {
  console.log('Ch-Ch-Changes');
});

db.replicate.to('http://example.com/mydb');



 
Countly  —基于插件的实时移动，Web和桌面分析平台，具有超过10个不同的SDK。 Countly还包括针对移动设备的大量推送通知和崩溃报告服务。
N1  —  一个开源的邮件客户端，建立在现代的Web技术之上，包括Electron，React和Flux。 它的设计是可扩展的，所以很容易创建围绕电子邮件的新体验和工作流程。 N1基于Nylas Sync Engine构建，这也是开源免费软件。 

Fabric.js 是一个让开发人员能够使用HTML5 canvas元素的框架，它是一个在canvas元素上的交互式对象模型。 它也是一个SVG-to-canvas解析器。


Mongotron  —  一个使用Electron和Angular JS构建的MongoDB GUI。

WebTorrent  —  浏览器中Streaming torrent客户端。WebTorrent is a streaming torrent client for node.js and the browser.

Video.js  —   一个开源的HTML5 & Flash视频播放器
Video.js是一个从头开始构建的HTML5视频播放器。 它支持HTML5和Flash视频，以及YouTube和Vimeo（通过插件）。 它支持在台式机和移动设备上播放视频。 这个项目于2010年年中开始，现在用户使用超过400,000个。


Reveal.js  — 一个框架，使用HTML轻松创建漂亮的演示文稿ppt。
在线示例.
reveal.js拥有丰富的功能，包括嵌套幻灯片，Markdown内容，PDF导出，演讲者备注和JavaScript API。 还有一个功能齐全的可视化编辑器和平台，用于在slides.com上分享reveal.js演示文稿。

Clipboard.js  — 现代拷贝到剪贴板。 无Flash。 只有3kb gzipped。


这是一个建立在D3之上的库，目的是改进我们如何处理大型和凌乱的图形。 它扩展了节点和链路与节点组的概念。 它非常适用于当多个节点事实上是同一事物或属于同一组时。



条码具有易操作、易维护的特点。对于室外场合，使用计算机登记信息非常不方便，通过使用条码，可以在操作现场将采集的条码信息传输到计算机。条码操作简便，极大地提高了系统的使用性。这里介绍分别甚至JavaScript实现的条形码相关开源库。

这里介绍分别甚至JavaScript实现的条形码相关开源库。

JsBarcode
JsBarcode 是一个生成条形码的开源库支持的有: CODE128 CODE128 (自动模式切换) CODE128 A/B/C (强制模式)等，在现代流量器上它会生成一个SVG矢量图用来生成条形码，使用如下：

var JsBarcode = require('jsbarcode');
var Canvas = require("canvas");

var canvas = new Canvas();
JsBarcode(canvas, "Hello");

// Do what you want with the canvas
// See https://github.com/Automattic/node-canvas for more information
项目主页： https://github.com/lindell/JsBarcode

quaggaJS
quaggaJS是由H5实现的JavaScript扫码库，能将条形码扫描成文字，支持静态图片和视频流的扫描。使用方法如下：

Quagga.init({
    inputStream : {
      name : "Live",
      type : "LiveStream",
      target: document.querySelector('#yourElement')    // Or '#yourElement' (optional)
    },
    decoder : {
      readers : ["code_128_reader"]
    }
  }, function(err) {
      if (err) {
          console.log(err);
          return
      }
      console.log("Initialization finished. Ready to start");
      Quagga.start();
  });
项目主页 https://github.com/serratus/quaggaJS


这是2016年JS1k上传的作品，用几十行代码实现的一个3D旋转魔方： 
作品地址 http://js1k.com/2016-elemental/demo/2611

Moment.js  — 一个用于解析，验证，操作和格式化日期的轻量级JavaScript日期库。
