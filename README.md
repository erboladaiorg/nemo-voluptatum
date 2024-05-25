# @erboladaiorg/nemo-voluptatum

## Install

Do not use it if you can use maps.

```sh
yarn add @erboladaiorg/nemo-voluptatum
```

or if npm is package manager of your choice

```sh
npm install @erboladaiorg/nemo-voluptatum --save
```

## Usage

### I want to create a new object

```js
import box from '@erboladaiorg/nemo-voluptatum';

const trackedObj = box({});
```

### I have an existing object

```js
import box from '@erboladaiorg/nemo-voluptatum';

const myObj = { 
  a: true,
  b: void 0,
};

const trackedObj = box(myObj);
// alternatively if you want to provide a custom orer
const trackedReversedObj = box(myObj, ['b', 'a']);
```

## LICENSE

[Apache License 2.0](https://github.com/erboladaiorg/nemo-voluptatum/blob/master/LICENSE)
