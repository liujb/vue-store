# Introduce

A vue plugin for use localStorage and cookie to store data. The feature

1. Not only compatible localstorage and cookie, but for browser private model.
2. Safety to write data on same domain.

# example

## Register

```
import VueStore from '../../assets/libs/js/vue-store'
Vue.use(VueStore, 'fatman')
```

## Usage

```
var obj = {
  name: 'Aslse',
  age: '23'
}
```

## As window property

```
window.$localStore.set('testobj', JSON.stringify(obj))
```

## As Vue instance property

```
let me = this
me.$localStore.set('testobj', JSON.stringify(obj))
```

# Affect

![affect](http://o77qh5rkr.bkt.clouddn.com/Screenshot%202016-05-23%2011.11.41.png)
