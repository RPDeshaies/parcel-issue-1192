# How to

```
npm install
npm start
```

Open `http://localhost:1234` in chrome

Go back in your editor and save either `A.ts` or `B.ts`

In the dev console you will see:


```
src.77de5100.js:58 Uncaught RangeError: Maximum call stack size exceeded
    at Function.resolve (src.77de5100.js:58)
    at localRequire (src.77de5100.js:55)
    at Object.eval (eval at hmrApply (index.ts:6), <anonymous>:7:11)
    at newRequire (src.77de5100.js:49)
    at hmrAccept (index.ts:6)
    at index.ts:6
    at Array.some (<anonymous>)
    at hmrAccept (index.ts:6)
    at index.ts:6
    at Array.some (<anonymous>)
    ...
```
