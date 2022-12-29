# Handy.js

## Find type
```js
export const isObject = (value) => value !== null && typeof value === "object";
export const isFunction = (value) => typeof value === "function";
export const isString = (value) => typeof value === "string";
export const isBoolean = (value) => typeof value === "boolean";
export const isNumber = (value) => typeof value === "number";
export const isUndefined = (value) => typeof value === "undefined";
```

## Number

```js
export const range = (min, max) => [...Array(max - min + 1).keys()].map((i) => i + min);
```
