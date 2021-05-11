To reproduce:

```sh
cd myapp
yarn
yarn ts-node src/index
```

Why does it die with:

```
mylib.hello();
      ^
TypeError: Cannot read property 'hello' of undefined
```


And why does TypeScript in `myapp` not error?
