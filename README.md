# ral-colors
Package containing all the RAL color information. [list of ral colors](https://en.wikipedia.org/wiki/List_of_RAL_colors)

## usage
```js
import { RAL } from 'ral-colors/index.js';

let classic_rals = RAL.classic;

//classic ral colors
console.log( RAL.classic.RAL1013 );

//effect ral colors
console.log( RAL.effect.RAL501 );

//design system ral colors
console.log( RAL.design_system.H010L50C45 );