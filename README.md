`libpng-next-1zy491fw4.now.sh`

```Installing build runtime...
Build runtime installed: 814.828ms
Looking up build cache...
Build cache found [38.21 MB, 18412 files]
Build cache unpacked: 1222.543ms
Installing dependencies...
npm WARN webp-loader@0.5.0 requires a peer of webpack-cli@* but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.9 (node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.9: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})

audited 18545 packages in 5.02s
found 2 vulnerabilities (1 moderate, 1 high)
  run `npm audit fix` to fix them, or `npm audit` for details
Running "npm run now-build"

> libpng-next@0.1.0 now-build /zeit/38645d23
> yum -y install libpng-devel && npm run build

Resolving Dependencies
--> Running transaction check
---> Package libpng-devel.x86_64 2:1.2.49-2.14.amzn1 will be installed
--> Processing Dependency: libpng = 2:1.2.49-2.14.amzn1 for package: 2:libpng-devel-1.2.49-2.14.amzn1.x86_64
--> Processing Dependency: libpng12.so.0()(64bit) for package: 2:libpng-devel-1.2.49-2.14.amzn1.x86_64
--> Running transaction check
---> Package libpng.x86_64 2:1.2.49-2.14.amzn1 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

================================================================================
 Package           Arch        Version                     Repository      Size
================================================================================
Installing:
 libpng-devel      x86_64      2:1.2.49-2.14.amzn1         amzn-main      116 k
Installing for dependencies:
 libpng            x86_64      2:1.2.49-2.14.amzn1         amzn-main      264 k

Transaction Summary
================================================================================
Install  1 Package (+1 Dependent package)

Total download size: 380 k
Installed size: 906 k
Downloading packages:
--------------------------------------------------------------------------------
Total                                              5.1 MB/s | 380 kB  00:00
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : 2:libpng-1.2.49-2.14.amzn1.x86_64                            1/2
  Installing : 2:libpng-devel-1.2.49-2.14.amzn1.x86_64                      2/2
  Verifying  : 2:libpng-1.2.49-2.14.amzn1.x86_64                            1/2
  Verifying  : 2:libpng-devel-1.2.49-2.14.amzn1.x86_64                      2/2

Installed:
  libpng-devel.x86_64 2:1.2.49-2.14.amzn1

Dependency Installed:
  libpng.x86_64 2:1.2.49-2.14.amzn1

Complete!

> libpng-next@0.1.0 build /zeit/38645d23
> next build

Creating an optimized production build...

Failed to compile.

./public/cars.png?webp
Error: PNG support not compiled. Please install the libpng development package before building.
Error! Could not process file /tmp/8b78fdb7-e84a-46c9-9956-e9c7c92bf49f
Error! Cannot read input picture file '/tmp/8b78fdb7-e84a-46c9-9956-e9c7c92bf49f'

> Build error occurred
Error: > Build failed because of webpack errors
    at build (/zeit/38645d23/node_modules/next/dist/build/index.js:9:900)
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! libpng-next@0.1.0 build: `next build`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the libpng-next@0.1.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /zeit/.npm/_logs/2019-11-15T14_05_03_719Z-debug.log
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! libpng-next@0.1.0 now-build: `yum -y install libpng-devel && npm run build`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the libpng-next@0.1.0 now-build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /zeit/.npm/_logs/2019-11-15T14_05_03_739Z-debug.log
Error: Exited with 1
    at ChildProcess.child.on (/zeit/ff717248bfa72cfe/.build-utils/.builder/node_modules/@now/next/dist/index.js:38207:24)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
worker exited with code 20 and signal null
done

```
