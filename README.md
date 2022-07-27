# React-countup-timer

A simple count up timer for react version greater than 16.

## Installation

```shell
npm install react-countup-timer
```

## Usage

```typescript jsx
import moment from "moment";
import CountUpTimer from "react-countup-timer";

<CountUpTimer startTime={moment().unix()}/>
```
Start the timer by providing the `startTime`, likewise, set `startTime` to `undefined` to stop the timer.

## Props

`startTime?: number | undefined` =>  The start time in the format of unix timestamp. 

