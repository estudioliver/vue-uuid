# vue-uuid-v4
Plugin Vue to easy get UUIDv4

# Requirements

- [Vue.js](https://github.com/vuejs/vue) `^1.0.0` (Compatible with Vue 1.0 or 2.0)
- A module bundler such as [webpack](https://github.com/webpack/webpack), or transpiler ES6.

# Installation

``` bash
$ npm install --save @estudioliver/vue-uuid-v4
```

# Usage
``` html
import Vue from 'vue'
import uuid from '@estudioliver/vue-uuid-v4'
import App from './App.vue'

// The plugin is loaded.
Vue.use(uuid)

new Vue({
  el: '#app',
  render: h => h(App),
  mounted() {
   console.log(this.$uuidKey) // --> b9c9aa52-16b8-4745-a945-2846c81eeb82
  }
});
```
