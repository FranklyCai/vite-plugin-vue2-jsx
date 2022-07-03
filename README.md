提供Vue2的JSX和TSX支持（包括HMR）
```js
// vite.config.js
import vueJsx from 'vite-plugin-vue2-jsx'

export default {
  plugins: [
    vueJsx({
      // options are passed on to @vue/babel-plugin-jsx
    })
  ]
}
```