# EventLogger

Cross platform Event Logger for NodeJS written in pure Javascript.

The Windows Event Logging portion is heavily inspired from [`node-windows`](https://github.com/coreybutler/node-windows).

## Operating Systems

- [ ] Windows
- [x] MacOSX
- [ ] Linux

## How to use

```js
const EventLogger = require('eventlogger')

const log = new EventLogger('Hello World')

log.info('Basic information.')
log.warn('Watch out!')
log.error('Something went wrong.')
```

## MacOSX

Using the `Console` users can capture/view application logs.

![darwin-console](images/darwin-console.png)