把赞赏码 / 收款码图片放在这个文件夹。

推荐文件名
  wechat.png     微信赞赏码
  alipay.png     支付宝收款码
  afdian.png     爱发电二维码

上传后，把下面这种 raw 地址写进仓库根目录的 creator.json：

  "qr": [
    {
      "label": "微信赞赏",
      "image": "https://raw.githubusercontent.com/zhi847699-cpu/Anima-Public/main/creator/wechat.png"
    }
  ]

买家打开软件会自动拉取 creator.json，无需重新打包。
