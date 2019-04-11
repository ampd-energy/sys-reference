# Sys Reference
System Alarm reference for dashboard

## What are these files?

### SysAlarmList
`SysAlarmList.json` is the database of System Alarms

## How to use them?

#### Install
```bash
npm install --save-dev git+ssh://git@github.com/ampd-energy/sys-reference.git
```

#### Import
```javascript
  // importing the whole as one object
  import SysRef from 'sys-reference'

  // of course you can also do this if you want to direcly reference individual object
  import { list } from 'sys-reference'
```
