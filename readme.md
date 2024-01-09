## 🚀 delete-others-log-loader

去除其他人的console.log(),保留自己的
Remove other people's console.log() and keep your own

### install
```
npm i delete-others-log-loader -D
```
### use

```js
module.exports = {
  module: {
    rules: [
      { test: /\.(js|ts|jsx|tsx|vue)$/, use: 'delete-others-log-loader' },
    ],
  },
};
```

### LICENSE
