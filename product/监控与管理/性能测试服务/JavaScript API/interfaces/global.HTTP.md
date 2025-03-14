## Properties（属性）
[](id:basicAuth)
### basicAuth
**basicAuth**: [`BasicAuth`](https://cloud.tencent.com/document/product/1484/75806)
```plaintext
Defined in typings/global.d.ts:265
```
HTTP Basic authentication
```plaintext
export const option = {
    http: {
        basicAuth: {
            username: 'user',
            password: 'passwd',
        }
    }
}
```


[](id:disableKeepAlives)
### disableKeepAlives
**disableKeepAlives**: `boolean`
```plaintext
Defined in typings/global.d.ts:224
```
是否禁用长连接
``` plaintext
export const option = {
    http: {
        disableKeepAlives: true
    }
}
```


[](id:discardResponseBody)
### discardResponseBody
**discardResponseBody**: `boolean`
```plaintext
Defined in typings/global.d.ts:277
```
是否丢弃回包
```json
export const option = {
    http: {
        discardResponseBody: true
    }
}
```

[](id:headers)
### headers
**headers**: `Record`<`string`, `string`\>
```plaintext
Defined in typings/global.d.ts:238
```
http 请求头
```json
export const option = {
    http: {
        headers: {
            'key': 'value'
        }
    }
}
```

[](id:http2)
### http2
**http2**: `boolean`
```plaintext
Defined in typings/global.d.ts:289
```
是否启用 HTTP2
```json
export const option = {
    http: {
        http2: true
    }
}
```

[](id:maxIdleConns)
### maxIdleConns
**maxIdleConns**: `number`
```plaintext
Defined in typings/global.d.ts:200
```
单个 VU 最大活跃连接数
```json
export const option = {
    http: {
        maxIdleConns: 50
    }
}
```

[](id:maxIdleConnsPerHost)
### maxIdleConnsPerHost
**maxIdleConnsPerHost**: `number`
```plaintext
Defined in typings/global.d.ts:212
```
单个 VU 单个域名最大活跃连接数
```plaintext
export const option = {
    http: {
        maxIdleConnsPerHost: 10
    }
}
```


[](id:maxRedirects)
### maxRedirects
**maxRedirects**: `number`
```plaintext
Defined in typings/global.d.ts:188
```
http 重定向跳转次数
```js
export const option = {
    http: {
        maxRedirects: 5
    }
}
```

[](id:timeout)
### timeout
**timeout**: `number`
```plaintext
Defined in typings/global.d.ts:250
```
请求超时时间，单位毫秒
```json
export const option = {
    http: {
        timeout: 3000
    }
}
```

