# click-outside-directive-VueJS
USING
------------

//main.js

import 'ClickOutsideDirective' from './directives/clickOutside'

Vue.directive('click-outside', ClickOutsideDirective)

---

//YourComponent

<div @click="show" v-click-outside="hide">
  <div>
    click outside me
  </div>
</div>
