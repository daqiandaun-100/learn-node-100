## [146 Node.js入门到企业Web开发中的应用 - 慕课网](https://github.com/nanana-100/imooc-146/tree/main)


### Process

* [`process.stdin`](https://nodejs.org/docs/latest-v22.x/api/process.html#processstdin)
* [`process.stdout`](https://nodejs.org/docs/latest-v22.x/api/process.html#processstdout)

### Stream

> All streams are instances of **EventEmitter**

**stream.Readable**

* [`readable.pipe`](https://nodejs.org/docs/latest-v22.x/api/stream.html#readablepipedestination-options)

> Event

* [`data`](https://nodejs.org/docs/latest-v22.x/api/stream.html#event-data)
* [`end`](https://nodejs.org/docs/latest-v22.x/api/stream.html#event-end)

**stream.Writable**

* [`writable.write`](https://nodejs.org/docs/latest-v22.x/api/stream.html#writablewritechunk-encoding-callback)
* [`writable.end`](https://nodejs.org/docs/latest-v22.x/api/stream.html#writableendchunk-encoding-callback)

> Event

* [`finish`](https://nodejs.org/docs/latest-v22.x/api/stream.html#event-finish)

### EventEmitter

* [`emitter.on`](https://nodejs.org/docs/latest-v22.x/api/events.html#emitteroneventname-listener)
* [`emitter.emit`](https://nodejs.org/docs/latest-v22.x/api/events.html#emitteremiteventname-args)
* [`emitter.once`](https://nodejs.org/docs/latest-v22.x/api/events.html#emitteronceeventname-listener)
* [`emitter.removeListener`](https://nodejs.org/docs/latest-v22.x/api/events.html#emitterremovelistenereventname-listener)

### Path

* [`path.resolve`](https://nodejs.org/docs/latest-v22.x/api/path.html#pathresolvepaths)
* [`path.join`](https://nodejs.org/docs/latest-v22.x/api/path.html#pathnormalizepath)

### File system

* [`fs.createReadStream`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fscreatereadstreampath-options)
* [`fs.createWriteStream`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fscreatewritestreampath-options)
* [`fs.watch`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fswatchfilename-options-listener)
* [`fs.stat`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fsstatpath-options-callback)、~~[`fs.exists`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fsexistspath-callback)~~
  * [`fs.Stats`](https://nodejs.org/docs/latest-v22.x/api/fs.html#class-fsstats)
* [`fs.readFileSync`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fsreadfilesyncpath-options)
* [`fs.readFile`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fsreadfilepath-options-callback)
* [`fs.writeFile`](https://nodejs.org/docs/latest-v22.x/api/fs.html#fswritefilefile-data-options-callback)

### Modules: CommonJS modules

* [`__dirname`](https://nodejs.org/docs/latest-v22.x/api/modules.html#__dirname)
* [`__filename`](https://nodejs.org/docs/latest-v22.x/api/modules.html#__filename)