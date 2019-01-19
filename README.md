### MProgress.js
---
https://github.com/lightningtgc/MProgress.js

```
bower install --save mprogress
npm install --save mprogress
```

```js
var mprogress = new Mprogress();
mprogress.start();

var mprogress = new Mprogress('start');
mprogress.end();

mprogress.set(0.3);
mprogress.inc();
mprogress.inc(0.3);

var bufferIntObj = {
  template: 2
};
var bufferProgress = new Mprgress(bufferIntObj);

bufferProgress.start();

var bufferIntObj = {
  template: 2,
  start: true
};
var bufferProgress = new Mprogress(bufferIntObj);

bufferProgress.end();

var intObj = {
  template: 3,
  parent: '#customId'
};
var indeterminateProgress = new Mprogress(intObj);

indeterminateProgress.start();
indeterminateProgress.end();

var intObj = {
  template: 4
  parent: '#anothercustomId'
};
var queryProgress = new Mprogress(intObj);

queryProgress.start();
queryProgress.end();

var mp = new Mprogress(configuration);

var mp = new Mprogress({
  tempalte: 2
});

var mp = new Mprogress({
  parent: '#customContainer'
});

var mp = new Mprogress({
  template: 4,
  start: true
});

var mp = new Mprogress('start');
```

```
```

