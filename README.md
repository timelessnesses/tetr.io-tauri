# TETR.IO but it is built in tauri

This is tetr.io but it is built in tauri for lower CPU/memory usage. (Not official binary just for educational purposes and make my life easier)  
Cosinder install official binary from tetr.io  
Not supported tetr.io plus and never be added

## Pros and cons

### Pro

- It consume less resource
- Smaller binary size
### Con

- It is somehow very laggy in tetr.io for some reasons

## Benchmark

- Electron  
![tetr.io cpu and memory usage](./tetr.io.png)  
- Edge  
![edge browser cpu and memory usage](./edge.png)
- Tauri  
![tauri cpu and memory usage](./tauri.png)

## How to get a binary

You likely need to download them from github [release page](https://github.com/timelessnesses/tetr.io-tauri/releases) or [build one yourself](#build)

## Build

Install node.js and follow this guide of [how to setup tauri build with your os](https://tauri.studio/v1/guides/getting-started/prerequisites) then run this command:

```bash
$ npm install
```

Then run this command:

```bash
$ npx tauri build
```

It should spit  binary src-tauri/target/release/tetr-io-tauri.exe
