# cortex-cdn-provider [![NPM version](https://badge.fury.io/js/cortex-cdn-provider.svg)](http://badge.fury.io/js/cortex-cdn-provider) [![Build Status](https://travis-ci.org/cortexjs/cortex-cdn-provider.svg?branch=master)](https://travis-ci.org/cortexjs/cortex-cdn-provider) [![Dependency Status](https://gemnasium.com/cortexjs/cortex-cdn-provider.svg)](https://gemnasium.com/cortexjs/cortex-cdn-provider)

CDN provider for cortex, including:

- combo server
- zip server


## Zip Server

```
/root
    |-- a
        |-- 0.1.0
                |-- a.js
        |-- 0.1.0.zip (dynamic or static)
        
        |-- 0.1.2
                |-- b.js
        |-- 0.1.2.zip (...)
        |-- 0.1.0-0.1.2.zip (dynamic)
```

#### normal

zip/a/0.1.0.zip

#### patch

zip/a/0.1.0~0.1.2.zip

#### batch

zip/a,b/0.1.0~0.1.2,0.1.0~0.2.3.zip  <- version server

## Combo Server



- css
  - dynamic css background 
  
- js
