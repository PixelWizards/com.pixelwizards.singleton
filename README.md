com.pixelwizards.singleton
=========================

[![openupm](https://img.shields.io/npm/v/com.pixelwizards.singleton?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.pixelwizards.singleton/)

A simple Unity implementation of the Singleton software pattern.

Usage
--------------

### Install via OpenUPM

The package is available on the [openupm registry](https://openupm.com). It's recommended to install it via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add com.pixelwizards.singleton
```

### Install via git url

Add this to your project manifest.json

```
"com.pixelwizards.singleton": "https://github.com/PixelWizards/com.pixelwizards.singleton.git",
```

OpenUPM Support
----------------

This package is also available via the OpenUPM scoped registry: 
https://openupm.com/packages/com.pixelwizards.singleton/

Prerequistes
---------------
* This has been tested for `>= 2018.3`

## Documentation

- [View Documentation](docs/index.md)

Content
----------------

### Sample

Example:

`public class MySingleton: Singleton<MySingleton>`
`{`
		`public void DoSomething()`
		`{`
		`}`
`}`

You can now reference the singleton via it's instance like so:

`MySingleton.Instance.DoSomething();`

Required dependencies
---------------
* None 
