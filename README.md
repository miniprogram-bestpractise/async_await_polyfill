# async_await_polyfill

微信小程序的 `async/await` polyfill

## 用法

将 `runtime.js` 文件放置到小程序代码中，然后需要使用 `async/await` 语法的 `js` 文件通通都需要引入该文件，引入的示例如下：

```js
import regeneratorRuntime from 'pathToPolyfill/runtime'
```