# is-string-helper

```javascript
var obj = [{id: 123, name: "test"}];
console.log(obj[0].id); // 123
```

```javascript
var obj = {};
console.log(obj[0].id); // error
```

```javascript
var obj = {};
console.log(is(obj, "[0].id", null); // null
```
