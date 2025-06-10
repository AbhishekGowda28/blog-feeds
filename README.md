Function to check for negative 0

```js
function checkForNegativeZero(num){
    return (1/num) === -Infinity
}
```

Other way is to use [Object.is](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is)

```js
function isNumberNegativeZero(num){
    return Object.is(num, -0);
}
```


## References

- https://wirfs-brock.com/allen/posts/128