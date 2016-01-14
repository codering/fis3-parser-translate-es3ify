# fis3-parser-translate-es3ify
FIS3 transform to convert ES5 syntax to be ES3-compatible

基于[es3ify](https://github.com/spicyj/es3ify)

install: 

npm i -g fis3-parser-translate-es3ify

usage： 

```js
fis.match('/components/antd/lib/**.js', {
    parser: fis.plugin("translate-es3ify")
})

```

其他类似工具
[https://github.com/sorrycc/es3ify-loader](https://github.com/sorrycc/es3ify-loader)