<p align="center">
  <img src="https://vue-atlas.com/branding_github.png">
</p>

---

A library of [Vue.js](https://vuejs.org) 2.x components.

![](https://img.shields.io/npm/v/vue-atlas.svg)

[Documentation](https://vue-atlas.com)

## Installation

[https://www.npmjs.com/package/vue-atlas](https://www.npmjs.com/package/vue-atlas)

```bash
# npm
npm install vue-atlas
```

```bash
# yarn
yarn add vue-atlas
```

## Quickstart

### Import all components

```javascript
import Vue from 'vue'

import Va from 'vue-atlas'
import 'vue-atlas/dist/vue-atlas.css'

Vue.use(Va, 'en')
```

### Import individual components

```javascript
import Vue from 'vue'

import { VaButton } from 'vue-atlas/src/Button'
import { VaSelect } from 'vue-atlas/src/Select'
import { VaDropdown } from 'vue-atlas/src/Dropdown'
import 'vue-atlas/dist/vue-atlas.css'

Vue.use(VaButton)
Vue.use(VaSelect)
Vue.use(VaDropdown)
```

Please [visit the documentation page](https://vue-atlas.com) for more detailed examples of each component.
