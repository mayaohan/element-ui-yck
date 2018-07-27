<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

# Element

- This framework is adapted from "element-ui", which is modified by the special needs of individual projects.

> A Vue.js 2.0 UI Toolkit for Web.

## Links
- Homepage and documentation
  - International users: http://element.eleme.io/#/en-US
  - Chinese users: http://element-cn.eleme.io/#/zh-CN
- [awesome-element](https://github.com/ElementUI/awesome-element)
- [FAQ](./FAQ.md)
- [Customize theme](http://element.eleme.io/#/en-US/component/custom-theme)
- [Preview and generate theme online](https://elementui.github.io/theme-chalk-preview)
- [Element for React](https://github.com/eleme/element-react)
- [Element for Angular](https://github.com/ElemeFE/element-angular)
- [Atom helper](https://github.com/ElemeFE/element-helper)
- Starter kit
  - [element-starter](https://github.com/ElementUI/element-starter)
  - [element-in-laravel-starter](https://github.com/ElementUI/element-in-laravel-starter)
- [Design resources](https://github.com/ElementUI/Resources) (working in progress)
- Boilerplate for bug reports
  - [CodePen](https://codepen.io/anon/pen/ozYpNA)
  - [JSFiddle](https://jsfiddle.net/gmve9d3p/)

## Install
```shell
npm install element-ui-yck -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'element-ui-yck'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'element-ui-yck'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.


## LICENSE
[MIT](LICENSE)
