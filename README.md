## IceCream

<svg t="1575751990262" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1465" data-spm-anchor-id="a313x.7781069.0.i0" width="*" height="*"><path d="M913.066667 110.933333C957.866667 155.733333 981.333333 215.466667 981.333333 277.333333c0 57.6-19.2 110.933333-57.6 153.6 19.2 29.866667 29.866667 66.133333 29.866667 102.4 0 51.2-19.2 100.266667-55.466667 136.533334-36.266667 36.266667-85.333333 55.466667-136.533333 55.466666-12.8 0-27.733333-2.133333-40.533333-4.266666-2.133333 0-2.133333 2.133333-4.266667 2.133333L102.4 977.066667c-6.4 4.266667-10.666667 4.266667-17.066667 4.266666-10.666667 0-21.333333-4.266667-29.866666-12.8-12.8-12.8-14.933333-29.866667-8.533334-46.933333l253.866667-616.533333c0-2.133333 2.133333-2.133333 2.133333-4.266667-2.133333-12.8-4.266667-25.6-4.266666-40.533333 0-51.2 19.2-100.266667 55.466666-136.533334 17.066667-17.066667 38.4-32 61.866667-40.533333 23.466667-10.666667 49.066667-14.933333 74.666667-14.933333 8.533333 0 17.066667 0 23.466666 2.133333h6.4c6.4 2.133333 12.8 2.133333 21.333334 4.266667h4.266666c8.533333 2.133333 14.933333 4.266667 21.333334 8.533333 2.133333 0 4.266667 2.133333 6.4 2.133333 6.4 2.133333 10.666667 6.4 17.066666 8.533334 0 0 2.133333 2.133333 4.266667 2.133333 89.6-76.8 230.4-72.533333 317.866667 14.933333z m-76.8 345.6c-8.533333-8.533333-12.8-21.333333-12.8-32 0-12.8 6.4-23.466667 14.933333-32 4.266667-4.266667 8.533333-6.4 12.8-10.666666 27.733333-27.733333 44.8-66.133333 44.8-104.533334 0-40.533333-14.933333-76.8-44.8-106.666666-53.333333-53.333333-140.8-57.6-198.4-10.666667 21.333333 34.133333 32 72.533333 27.733333 113.066667-2.133333 23.466667-19.2 40.533333-42.666666 40.533333h-2.133334c-23.466667-2.133333-40.533333-21.333333-40.533333-44.8 2.133333-29.866667-8.533333-59.733333-29.866667-81.066667l-6.4-6.4-8.533333-8.533333c-4.266667 0-6.4-2.133333-8.533333-2.133333l-12.8-6.4c-2.133333-2.133333-6.4-2.133333-8.533334-2.133334-4.266667 0-6.4-2.133333-10.666666-2.133333-6.4 0-10.666667-2.133333-17.066667-2.133333h-4.266667c-21.333333 0-42.666667 6.4-59.733333 17.066666l-4.266667 4.266667c-4.266667 2.133333-8.533333 6.4-10.666666 8.533333-40.533333 40.533333-40.533333 108.8 0 151.466667l270.933333 270.933333c42.666667 40.533333 108.8 40.533333 151.466667 0 19.2-19.2 32-46.933333 32-74.666666 0-29.866667-10.666667-55.466667-32-78.933334 2.133333 2.133333 0 2.133333 0 0zM164.266667 859.733333l462.933333-189.866666-273.066667-270.933334-189.866666 460.8z" fill="#2F3CF4" p-id="1466" data-spm-anchor-id="a313x.7781069.0.i4" class=""></path></svg>

## 索引
> #### 它是什么 ？
> #### `Server` `Group` `Client` 它们分别是什么 ？


## 正文
### 1. 它是什么？
> **IceCream** 是一套 `云控` + `群控` 系统的结合。能够通过 `Group` 系统操作 ， 也可以不需要依靠 `Group` 运行。

### 2. `Server` `Group` `Client` 它们分别是什么 ？
> **Server** 是 `IceCream` 的 PHP 服务器端，它基于 `Laravel` 开发。提供了如 `验证` `登陆` `注册` `激活` 等基础功能 API.

> **Group** 是 `IceCream` 的 Windows 客户端，它是基于 `C# .NET` + `CefSharp` + `ADB` 等技术开发的；它实现了能够通过 `WebSocket` 与 `Server` 端双向通讯。以及通过 `ADB` + `Socket` 与 `Client` 端进行双向通讯

> **Client** 是 `IceCream` 的 Android 客户端；它是基于 `Auto.JS 4.1.1` 开发的。实现了对 `Server` 端的单向通讯，以及对 `Group` 端的双向通讯。
