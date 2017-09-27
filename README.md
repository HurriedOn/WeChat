# WeChat
WeChat small program

## 微信小程序与HTML5比较
* 相同点
   * 轻松跨平台。  
* 不同点
   * JavaScript限制：通过字符串传入来执行代码的能力都禁止了，与BOM相关的API都没有。
   * 登录方面：小程序通过wx.login获取code，避免登录前的重定向。
   * 存储方面：小程序用storage代替了HTML5中的localstorage、sessionstorage等。
   * 支付方面：微信支付路径不再受限制。
* 不足之处
   * 每个页面都需要手动在app.json中注册。
   * 代开页面有5个限制。
