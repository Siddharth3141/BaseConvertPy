# Base Change

An easy way to switch between bases in Python.

# Usage

#### Install

`pip install baseconvertpy`

#### Import

`import baseconvertpy`

#### Converting bases

```
baseconvertpy.convert(<Number>, <New Base>, <Original Base (Default is 10)>, <Charset (Default is characters for up to base 62)>)
```

#### Converting from base 10 to base X

```
baseconvertpy.to_baseX(<Number in base 10>, <New Base>, <Charset (Default is characters for up to base 62)>)
```

#### Converting from base X to base 10

```
baseconvertpy.to_base10(<Number in base X>, <Original Base>, <Charset (Default is characters for up to base 62)>)
```