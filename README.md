# markdownDep
markdownDep is develop on markdown 

### serialize
```js
 let el,el2;
 [el,el2].map(d=>Object.create(d.dataset)).reduce((a,b)=>Object.assing(a,b),{})

```
### draft
index.html
```
save to localStorage.
+ is new generate the key.
|ctl| key |filename(max16)   |description(max32)    |lines|update time|ctl|unwatch
|[+]|
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]
|[E]|key|filename[E]|description[E]|lines|updatetime|[DL]|  [UN]

send to key;
dep.html?key=mdcode.xyzeeee
```
