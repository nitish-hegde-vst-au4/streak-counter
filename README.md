# streak-counter
a streak counter for the browser, inspired by Duolingo

## Install

```shell
yarn add @nitish-hegde-vst-au4/streak-counter
```

## Usage

```javascript
import {streakCounter} from "@nitish-hegde-vst-au4/streak-counter"

const today = new Date()
const streak = streakCounter(localStorage, today)
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "17/01/2023",
//    startDate: "17/01/2023",
// }
```
