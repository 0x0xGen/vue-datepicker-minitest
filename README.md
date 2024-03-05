## Features

- Single date picker
- Range date picker
- Time picker
- Month picker
- Year picker
- Quarter picker
- Week picker
- Multiple dates select
- Multiple calendars
- Text input
- UTC support
- Timezones
- Locale support
- Week numbers
- Custom `v-model`
- Dark and light theme
- SSR support
- Highly configurable
- Accessible
- Included type definitions

## Install

```shell
yarn add @vuepic/vue-datepicker

# or

npm install @vuepic/vue-datepicker
```

Import and register component

**Global**

```js
import { createApp } from 'vue';
import App from './App.vue';

import VueDatePicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css';

const app = createApp(App);
app.component('VueDatePicker', VueDatePicker);
```

**Local**

```vue
<script>
    import VueDatePicker from '@vuepic/vue-datepicker';
    import '@vuepic/vue-datepicker/dist/main.css';
    
    export default {
        components: { VueDatePicker }
    }
</script>
```

## Supporting the project

As you may know, maintaining an open-source project is a very time-consuming job. Your support is very appreciated ❤️

Please ⭐️ this repository if you like the component!

You can also make a financial contribution via sponsoring this project or one time donation. [Become a sponsor](https://github.com/sponsors/Vuepic)

Special thanks to our sponsors 🙏

<a href="https://hapio.io/" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/99868704?s=200&v=4" width="80" alt="Hapio">
</a>

<a href="https://datagridvue.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/nruffing/data-grid-vue/049baf296f814e3b03faf48632a7508305e14ffc/vuepress/.vuepress/public/favicon.svg" width="80" alt="Data Grid Vue
">
</a>

## Versioning

This project follows [SemVer](https://semver.org) specification

## License

Copyright © 2021-present [Vuepic](https://github.com/Vuepic)

[MIT](https://github.com/Vuepic/vue-datepicker/blob/master/LICENSE)
