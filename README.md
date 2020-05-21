click-outside-directive-VueJS

USING
------------

//main.js
```php

import 'ClickOutsideDirective' from './directives/clickOutside'

Vue.directive('click-outside', ClickOutsideDirective)
```

//YourComponent
```html
<div v-click-outside="hide">
  <div>
    click outside me
  </div>
</div>
```
