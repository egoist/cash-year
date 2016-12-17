# cash-year

Like lodash but for year.

## Install

```bash
npm install --save cash-year
```

## Usage

### ES6

```js
const $year = require('cash-year')
```

### ES6 modules

```js
import * as $year from 'cash-year'
// or named import
import {isLeap} from 'cash-year'
```

## API

### .isLeap([year])

**year**

Type: `number`<br>
Default: `Current UTC year`

Check if a year is leap year.

```js
$year.isLeap(2016)
//=> true
```

### .days([year])

**year**

Type: `number`<br>
Default: `Current UTC year`

Get number of days in a year.

```js
$year.days(2014)
//=> 365
```

### .monthDays([month], [year])

**month**

Type: `number`<br>
Default: `Current UTC month`

**year**

Type: `number`<br>
Default: `Current UTC year`

Get number of days in a month within a year.

```js
$year.monthDays(1, 2016)
//=> 29
```
