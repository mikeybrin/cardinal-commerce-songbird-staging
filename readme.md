## cardinal-commerce-songbird

> An unaltered package mirror of [Cardinal Commerce's Songbird](https://cardinaldocs.atlassian.net/wiki/spaces/CC/pages/557065/Songbird.js) library

### Why Global Object?
Cardinal Commerce's songbird attaches itself to the window object, in an effort to not alter what source they've provided through their documentation, this module mirrors that decision.

### Transparency
In the interest of transparency, please check and compare the original source at https://songbirdstag.cardinalcommerce.com/edge/v1/songbird.js
### Usage

```javascript
import "cardinal-commerce-songbird-staging";

//Cardinal now available on window object
Cardinal.setup(...)
```

### Install
```
npm install --save cardinal-commerce-songbird-staging
```